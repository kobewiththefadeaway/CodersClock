# DoomsDayClock


# DoomsDayClock
Read me - creation process 

///////Alarm Clock interaction is contained in index.html////
Structure Created by html only, browser should display results

Alarm Clock Structure 

Made heading for the alarm clock using the <h1> tag and will center the text by utilising  inline CSS as well .

Created container using div tag which will contain the div of our hour minute and second clock hand. Two br (break tags used) to add two line spaces after the container tag and also added a horizontal row using the <hr> tag 

Created input type of date- time for taking the input of date and time from the user 

Created two buttons one for sleep and one for stop function, Additionally I will provide both of them an on-click function 

////Adding CSS Code ///// 

Structure will be mostly styled using the classes we defined inside html element , Id selector will be mostly used for this project reason for that being all the elements need to be styled individually to add the clock look 


-alarm clock backdrop will be given light blue color by using body tag , clocks container will be now styled using the id selector (#clockContainer). Position is set to relative and margin is set to auto using the background and the url attribute, also upload image of a clock with dimensions of 40vw in width and height ,it is set to 100% for background width 


Adding the clocks hour minute and second hands using CSS utilising the id selector (hour,minute,second)

First I’ve added a standard style with a border radius of 10 px , background black color and position that is relative 

Now to specify the style of our clock hour hand 1,8% of the width and 25% of the height are set .Using the top and left characteristics I leave a space of 48,25 % from the top and a space from the left , opacity is set to 0.8 using the opacity property 

///// vw - view width 1vw of the width of the viewport ////

Similarly I add styling to our minute and second hands 


*****Using JS ideas I will add styles to html components which will be added to the external CSS file.
Will be adding relative position using audio class , on top of that setting left and right margins to auto using the margin-left and margin-right  Dimensions are to 40 vw for both height and width 

Additionally I’ve styled input and button by using the id selector , Alarm clock’s input and button now have a 28 px font size 

****** Adding JS code 

To store the url to our alarm clock sound , I’ve created a variable called alarmSound and use new Audio() constructor to get that sound 

Created a new function called setAlarm (button) and I will pass parameter called button , inside of it value of HTML element using the document.getElementByld. will be stored. Also using additional statement if the value of the variable is NaN (Not a Number) and it will show an alert hopefully (invalid date)

Created a var called alarm which will be used In getting the date from user using new Date()  which creates a new date object with current date and time 

Using the conditional statement I will check whether the set alarm time is less than to the actual time ,then it will show an alert time passed 

Using the setTimeOut method we will add a time out to the cancel alarm button as the user click on it the time is reset 
