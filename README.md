# Countdown Timer
 Simple countdown timer for Windows

This is a simple Windows Forms countdown timer I created to fight distraction. I'd start something in the kitchen, get distracted on the computer, and then burn whatever I was cooking, so I built this to warn myself.

![image](https://www.geoffstratton.com/sites/default/files/images/countdown.jpg)

The program takes user input into a masked textbox, uses the Systems.Windows.Forms.Timer class to count down while displaying the remaining time, and then beeps at you when it reaches 00:00. It still works in Windows 7 x64 using the .NET 4.6 framework.

The code would go in Form1.cs or equivalent. Designer.cs and Program.cs were left untouched (by me) in this case. The only other relevant setting not shown here is timer1.Interval = 1000 (set in the form designer), which defines the frequency of elapsed timer events (like the tick) in milliseconds.

License
---------------
GNU General Public License v3.0

Author
---------------
Geoff Stratton
