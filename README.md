# Digital Timer
 
Include your responses to the bold questions below. Include snippets of code that explain what you did. Deliverables are due next Tuesday. Post your lab reports as README.md pages on your GitHub, and post a link to that on your main class hub page.

## Part A. Solder your LCD panel

**Take a picture of your soldered panel and add it here!**

![Image1](https://github.com/ZhenweiZhang1995/IDD-Fa19-Lab2/blob/master/lab2_1.jpeg)

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?**  
5V

**b. What voltage level do you need to power the display backlight?**  
3.3V
   
**c. What was one mistake you made when wiring up the display? How did you fix it?**  
I only connect the long breadboard vertically on one side and forget the other side beneath the LCD panel. I later figured that out and connected them.

**d. What line of code do you need to change to make it flash your name instead of "Hello World"?**  
`lcd.print("hello, world!");`  
Change "hello world" to "Zhenwei" 
 
**e. Include a copy of your Lowly Multimeter code in your lab write-up.**
[Multimeter code](https://github.com/ZhenweiZhang1995/IDD-Fa19-Lab2/blob/master/Multimeter.ino)


## Part C. Using a time-based digital sensor

**Upload a video of your working rotary encoder here.**  
[Link to video](https://youtu.be/hi7m0yVBmh4)

## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**  
Change `int noteDuration = 1000 / noteDurations[thisNote];` to `int noteDuration = 1000 / noteDurations[thisNote]/2;` (Decrease noteDuration by half)
 
**b. What song is playing?**


## Part E. Make your own timer

**a. Make a short video showing how your timer works, and what happens when time is up!**

**b. Post a link to the completed lab report your class hub GitHub repo.**
