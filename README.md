# AlarmClass
Class representing an Alarm Clock
This class(AlarmClock(object)) allows to set a current time and alarm time(instance attribiute). It calculates the time remaining 
( by second_remaining(self) method) until the alarm and can display it (by display_remain(self) method) and waits until the alarm goes off, providing a notification( by alarm_after_seconds(self) method) when the time is up.

i define func (set_clock_and_alarm()) to Set the current time and alarm time, and trigger the alarm with (to use class)
This function prompts the user to input the current time and the alarm time in HH:MM:SS format. 
It creates an instance of the AlarmClock class, and call method alarm_after_seconds() to run 
 
