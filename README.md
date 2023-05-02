Download Link: https://assignmentchef.com/product/solved-cmis102-lab1-hands-on-lab
<br>
Week 1Overview This hands-on lab demonstrate a simple sequential print statements using an online C compiler such as ideone.com. You should follow the instructions to complete the lab as well as perform the learning exercises at the end of this lab.Instructionsa. Open up any online C compiler (e.g repl.it or ideone.com). b. Be sure the C Language is selected. c. Enter the code below into the editor. (Note: LEO doesn’t let you just copy and paste from this document so you can either download the document and then copy and paste or just go to the Code for HelloWorld link for this week and copy and paste from there.) d. Click the submit, or run button. e. Try the additional learning exercises on the next page.Here is what the “Hello, World” looks like using repl.it after a successful run. You will need to set up a free account in this IDE, and select a project language, in this case C, which will create the basic “Hello World” project for you.

Run the programSource Code PanelInput/Output Panel2

Here is what “Hello, World!” Looks like using ideone.com after it has successfully run

Hello, World C code#include &lt;stdio.h&gt; int main(void) { printf(“Hello: World?”); return 0; }

Learning Exercises for you to complete1. Demonstrate you successfully followed the steps in this lab by preparing screen captures of you running the lab as specified in the Instructions above. 2. Remove the semi-colon (;) at the end of this statement:

printf(“Hello: World?”);

Describe what happens. Why is the semi-colon needed?

3. What happens if you add another printf statement such as:

printf(“.. Bye ..”); after the printf(“Hello: World?”); line?

Describe the new output. Be sure to support your description with screen captures of executing the new code.3

4. Experiment by adding additional printf statements to your code such as:printf(“.. Bye .. 
”);printf(“Hello &amp; again! 
”);What does the “
” do to the output?Be sure to experiment by adding several printf statements and describe the resulting output. Be sure to support your description and experimentation with screen captures of executing the new code.

5. (Optional) For more fun, try some of the following experiments: a. Add some comments using the // token. Everything after that token on a line is ignored. b. Try commenting out (adding a // at the start of a line) line 1. What happens? UNDO this change before trying any other experiments! c. What happens if line 5 is commented out? d. Try the /* … */ style commenting. e. Add a header block of comments using the following syntax: // File: myFile.cpp // Date: month day, year // Author: my name // Purpose: get the IDE working f. Try the following header comment block format: /* File: myFile.cpp *Date: month day, year * Author: my name * Purpose: get the IDE working */ g. Add a printf statement telling the user who wrote this program – something like the following: printf (“Hello world written by Jane Doe
”); h. Experiment with the 
 token. Some ideas: move it around, split up the  and the n, use more than one, leave off the .