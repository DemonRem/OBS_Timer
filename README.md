# OBS Timer
## Author: Mike Bethany
### mikebethany.com


**Description:**  
OBS Timer is a very simple countdown timer that outputs a text file you can use in the Open Broadcast Software streaming app.  

I wrote this app specifically for use with iRacing but it can be used with any 15 minute interval thing you want to do.  

I didn't want a billion options and I didn't want to have to constantly reset the time or do press a button 45 times to get the timer set.  

I also wanted it to be as automatic as possible to it does a lot of the work for you like setting the time automatically, turning off the text when the countdown is done, and automatically making buttons with the next three hours in 15 min increments.  

If you want a bewildering amount of options check out Snaz:  
https://obsproject.com/forum/viewtopic.php?f=22&t=2489  

**Usage:**  
Start the program. The time will be set automatically.  

Type whatever text you want in the message box, this will be saved for the next time you open the app.  

The countdown timer will be added to the end of your text and saved to the output text file.  

The file is located in the same directory as the application which should be:  
C:\Program Files (x86)\OBS Timer\obs_timer_text.txt  

The buttons below the message box are how you set the countdown timer.  

To stop the count down press the stop button, close the app, or wait for the timer to run down.  
When the countdown ends the text file will be set to empty so in OBS the text effectively goes away:  
no need to micromanage the timer.  

**Version History:**  
0.2.0 - 2014.02.15  
Added timer offset.   
  
0.1.0 - 2014.01.14 - Initial Release  