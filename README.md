# Countdown_timer
The code will take input from the user regarding the length of the countdown in seconds. After that, a countdown will begin on the screen of the format ‘minutes:seconds’. 
Module to be used: time module
Function to be used: sleep() function

1.We will import the time module.
2.We will then ask the user to input the length of countdown in seconds.
3.This value is sent as a parameter ‘t’ to the user- defined function countdown(). Any variable read using input function is a string. So, we type convert this parameter to ‘int’ as it is of string type.
4.In this function a while loop runs till time becomes 0.
5.We then use divmod() to calculate the number of minutes and seconds. You can read more about it here.
6.Then we will print the minutes and seconds on the screen using the variable timeformat.
7.Using end = ‘\r’ we force the cursor to go back to the start of the screen (carriage return), so that the next line printed will overwrite the previous one.
8.time.sleep() is used to make the the code wait for one sec.
9.We then decrement time so that the while loop can converge.
10.After the completion of the loop we will print “Fire in the hole” to signify the end of the countdown.
