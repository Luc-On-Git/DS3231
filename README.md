# DS3231
Library written in C for DS3231 board (RTC/Temperature/memory).
This library is currently used with STM32L476G microcontroler but it is buid so that any other microcontroler can be used.
Only communication routines must be changed (improvements to come:group the transmission routines witch are currently spreaded in the code).
Note : Alarms are not implemented (to do).
The use of 'extern' declarations in main.c is necessary to get the most of the functionalities:pick up variables in DS3231.c
The two files have to be put in the right folders.
Values used to reset the device are those found in the datasheet. Obviously, these values can be changed.
Please notice that time is printed without taking care of the format used inside the DS3231. This behavior can be changed in the main routine.
In this case, little lines of code are required.
Enjoy...
