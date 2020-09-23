<div align="center">

## Colored Text


</div>

### Description

This program is a very basic animation. It uses the conio.h header file. It goes to the center of the screen, sets the text color, pauses for a second, and then resets the text and background color and prints more text. This is a verrrrrrrry basic animation.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kevin Browns](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kevin-browns.md)
**Level**          |Beginner
**User Rating**    |4.0 (24 globes from 6 users)
**Compatibility**  |C\+\+ \(general\), Borland C\+\+
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__3-15.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kevin-browns-colored-text__3-1401/archive/master.zip)





### Source Code

#include stdio.h<br>
#include conio.h//you MUST have this header for this prog to work
<br>
#include dos.h//for the sleep() function<br>
void ColoredText();//prototype for text doloring function
<br>
int main() {<br>
 ColoredText();//calling of the function<br>
 }<br>
void ColoredText() {//Ladies and Gentlemen...The function!!<br>
 <br>clrscr();//we clear the screen
 <br>gotoxy(24,1);//go to the 'x' 24 and the 'y' 1
 <br>textcolor(GREEN);//set the text to green
 <br>         //the color has to be<br> <br>uppercase
 <br>cprintf("This is it!!");//the 'c' before the <br.printf stands for 'color'
 <br>sleep(1);//take a good look at it for 1 <br>second
 <br>textcolor(BLUE);//reset the text color
 <br>textbackground(YELLOW);//Hey! Advanced! <br>setting the backround behind the text to <br>yellow
 <br>clrscr();//clearing the screen
 <br>gotoxy(24,1);//moving to the center
 <br>cprintf("More of it!");//again we print
 <br>sleep(1);//zzzzzzz!
 <br>clrscr();//finally clearing the screen
<br>}

