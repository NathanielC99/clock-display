Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.

Answers 
1)It starts at this time because that's when most clocks start at.
3)It would take 60 times, and you can just set it to "1:00".
5)public Rectangle window(length,width);
6)It creates the clock at the set time you put in.
7)It does not have a call to updateDisplay because it sets the display to the imputed time.
8)1.System.out.println(filname);
    System.out.println(doubleSided);
  2.return delay
9)two squares, a triangle and a circle.
10)changeSize, moveHorizontal, moveVertical, and makeVisable.
11)yes.
12)
Note: This project does not implement adequate handling of errors.
