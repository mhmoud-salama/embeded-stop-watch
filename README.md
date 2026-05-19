The project is to utilize the NUCLEO-F401RE development board in conjunction with an Arduino Multifunction Shield to create a real-time embedded application that demonstrates fundamental principles of digital interfacing, analog signal processing, and time-based operations.
The system is designed to perform two primary functions:
1.	Real-Time Clock (RTC): Upon startup or reset, the 7-segment display begins counting time from 00:00 in minutes and seconds. The counter continues to increment every second until it reaches a defined maximum value or is reset by the user.
2.	Analog Voltage Display: When a specific button (S3) is pressed, the system switches to a mode where it reads the analog voltage from the on-board potentiometer and displays the value in volts on the 7-segment display. Once the button is released, the system resumes time display without interrupting the background clock.

How It Works 
System boots → clock starts.
Every second: total_seconds increments.
User can:
  o	Press S1: reset time to 0.
  o	Press S3: switch display to show voltage.
Even while in voltage mode, the clock continues running in the background.
<img width="3000" height="4000" alt="IMG20250508170104" src="https://github.com/user-attachments/assets/ec294867-f159-46fb-ab2a-9f9409be0fac" />
<img width="3000" height="4000" alt="IMG20250508170106" src="https://github.com/user-attachments/assets/cbbdcd28-76e7-47bd-9b62-2e134ea2f17d" />




[Embeded Project.pdf](https://github.com/user-attachments/files/27979590/Embeded.Project.pdf)

