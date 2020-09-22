<div align="center">

## Basics of C/C\+\+: Part III\-\-Loops


</div>

### Description

This is the third installment of the Lessons in C programming tutorials created by me, Alexander. In this lesson I will cover loops. Loops basically do what it sounds like, loop. If you have read lesson 2 you should understand some Boolean expressions. If you do not, you should read it again. When working with loops it is important to understand truth and false. Maybe you should try doing some truth tables with problems.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Alexander of CProgramming\.com](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/alexander-of-cprogramming-com.md)
**Level**          |Beginner
**User Rating**    |4.2 (21 globes from 5 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Data Structures](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/data-structures__3-8.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/alexander-of-cprogramming-com-basics-of-c-c-part-iii-loops__3-443/archive/master.zip)





### Source Code

<p><font face="Verdana">There are basically 3 types of loops. FOR, WHILE, DO
WHILE Each of them has their uses.&nbsp; They are all outlined below.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; FOR - FOR loops are the most
useful type, I believe. The layout is for(variable initialization, conditional,
incrementing variable) It is very versatile, and the layout can be changed
somewhat. Basically, the variable initialization allows you to either declare a
variable and give it a value, or give a value to another variable. Second, the
conditional statement. What it does is it says that while the conditional is
true then it would do what in is in the body. Third, the incrementing variable
section. It does not have to increment a variable. It can decrement, which is
subtracting one, or it can perform various other manipulations on the variable.</font></p>
<p><font face="Verdana">Ex. #include &lt;iostream.h&gt; //We only need one
header file</font></p>
<p><font face="Verdana">void main() //We always need this</font></p>
<p><font face="Verdana">{<br>
//The loop goes while x&lt;100, and x has one</font></p>
<p><font face="Verdana">for(int x=0;x&lt;100;x++)/*THE LOOP*/ //added to it
every time the loops</font></p>
<p><font face="Verdana">{</font></p>
<p><font face="Verdana">cout&lt;&lt;x&lt;&lt;endl; //Outputting x</font></p>
<p><font face="Verdana">}</font></p>
<p><font face="Verdana">}</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; This program is a very simple
example of a for loop. x is set to zero, while x is less than 100 do cout&lt;&lt;x&lt;&lt;endl;
add 1 to x until the loop ends. Pretty simple to understand, but it is a very
powerful loop, and much better than WHILE and DO WHILE loops.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; WHILE - WHILE loops are very
simple, but not as useful as FOR loops. The basic structure is...WHILE(true)
then do whatever is in the body. The truth could be x==1 or while(x!= 7)&nbsp;
(x does not equal 7)</font></p>
<p><font face="Verdana">Ex. #include &lt;iostream.h&gt; //We only need this
header file</font></p>
<p><font face="Verdana">void main() //Of course...</font></p>
<p><font face="Verdana">{ int x=0; //Don't forget to declare variables</font></p>
<p><font face="Verdana">while(x&lt;100) //While x is less than 100 do</font></p>
<p><font face="Verdana">{</font></p>
<p><font face="Verdana">cout&lt;&lt;x&lt;&lt;endl; //Same output as the above
loop</font></p>
<p><font face="Verdana">x++; //Adds 1 to x every time it repeats</font></p>
<p><font face="Verdana">}</font></p>
<p><font face="Verdana">}</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; This was another pretty simple
example, but it is longer than the above FOR loop, showing why I like for better
than while, though while is a very easy loop to use, so if you are having
trouble then you can use it, but try to use for.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; DO WHILE - DO WHILE loops are
useful for only things that want to loop at least once.&nbsp; Basically it goes
DO { THIS } WHILE(TRUE) Now, it is your turn to try and do a loop! make a DO
WHILE loop that does what the above programs do...output 0 to 99! It is not
hard, if you have trouble email me at lallain@concentric.net and I will give you
some help... Best of luck :)</font></p>

