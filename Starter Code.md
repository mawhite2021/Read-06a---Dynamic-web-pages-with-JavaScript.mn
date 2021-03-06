#**How HTML,CSS, Javascript, FIT**

There are three languages used to create web pages:
HTML-*CONTENT LAYER*
. html files <html>
This is where the content of
the page lives. The HTML gives
the page structure and adds
semantics.

Javascript-PRESENTATION LAYER
. css files {css}
The CSS enhances the HTML
page with rules that state how
the HTML content is presented
(backgrounds, borders, box
dimensions, colors, fonts, etc.).

CSS-BEHAVIOR LAYER
.js files ()Javascript
This is where we can change
how the page behaves, adding
interactivity. We will aim to keep
as much of our JavaScript as
possible in separate files. 

**Progressive Enhancement**
These three layers form the basis of a popular
approach to building web pages called
progressive enhancement.

**HTML ONLY**
Starting with the HTML layer
allows you to focus on the most
important thing about your site:
its content.
Being plain HTML, this layer
should work on all kinds of
devices, be accessible to all
users, and load quite quickly on
slow connections. 

**HTML+CSS**
Adding the CSS rules in a
separate file keeps rules
regarding how the page looks
away from the content itself.
You can use the same style sheet
with all of your site, making your
sites faster to load and easier
to maintain. Or you can use
different style sheets with the
same content to create different
views of the same data. 

**HTML+CSS+JAVASCRIPT**
The JavaScript is added last
and enhances the usability of
the page or the experience of
interacting with the site.
Keeping it separate means
that the page still works if the
user cannot load or run the
JavaScript. You can also reuse
the code on several pages
(making the site faster to load
and easier to maintain).

**The ABCs Of Programming**
It is best to keep javascript Code in it's own javascript file. Javascript files are text files, but they only have .js extension.
The HTML <script> element is used in HTML pages to tell browsers to load the javascript file.
If you view the source code of the page in the browser, the javascript would not have changed HTML, because the script works with the model of the web page that the browser has created.
  
  **Statements**
  A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a **statement.**
*Statements should end with a semicolon.*

**STATEMENTS ARE INSTRUCTIONS** 
AND EACH ONE STARTS ON A NEW LINE

A **statement** is an individual instruction that the
computer should follow. Each one should start on a
new line and end with a semicolon. This makes your
code easier to read and follow.
The semicolon also tells the JavaScript interpreter
when a step is over, indicating that it should move
to the next step. 

Some statements are surrounded by curly braces;
these are known as **code blocks**. The closing curly
brace is not followed by a semicolon.

**Comments**- you should write comments to explain what the code does. They make your code more easier to read and understand.

**MULTI-LINE COMMENTS**

To write a comment that stretches over more than
one line, you use a **multi-line comment**, starting with
the /* characters and ending with the */ characters.
Anything between these characters is not processed·
by the JavaScript interpreter.

*Multi-line comment s are often used for descriptions
of how the script works, or to prevent a section of
the script from running when testing it.*

**SINGLE-LINE COMMENTS**
*In a single-line comment, anything that follows the
two forward slash characters I/ on that line will not
be processed by the JavaScript interpreter. Singleline comments are often used for short descriptions
of what the code is doing.*

#**What Are Variables?**
A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
*A variable is a good name for this
concept because the data stored
in a variable can change (or vary)
each time a script runs.*

**Variables & How to Declare them**
Before using a variable you need to annouce that you want to use it. This involves creating the variable and giving it a name.
*Programmers say that you declare the variable.*

Var is a example of what programmers call a keyword.
Once you have created a variable, you can tell it what information you want it to store for you.
*Programmers call this assign a value to the variable.*

**Data Types**
JavaScript distinguishes between numbers,
strings, and true or false values known as
Booleans.
NUMERIC DATA TYPE
The numeric data type handles
numbers.
0.75

STRING DATA TYPE
The strings data type consists of
letters and other characters. 

BOOLEAN DATA TYPE
Boolean data types can have one
of two values: true or false. 

**Using A variable To Store a Number**
Here, three variables are created
and values are assigned to them:

• price holds the price of an
individual tile
• quantity holds the number
of tiles a customer wants
• to ta 1 holds the total cost of
the tiles 

**Short hand for creating Variables**
Here are three variations of how
to declare variables and assign
them values:
1. Variables are declared and
values assigned in the same
statement.
2. Three variables are declared
on the same line, then values
assigned to each.
3. Two variables are declared
and assigned values on the same
line. Then one is declared and
assigned a value on the next line.

 **Six Rules For Naming Variables**
 Here are six rules you must always follow when giving a variable a name: 
 
 1. The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number. 

2.The name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name.

3.You cannot use keywords or
reserved words. Keywords
are special words that tell the
interpreter to do something. For
example, var is a keyword used
to declare a variable. Reserved
words are ones that may be used
in a future version of JavaScript.
ONLINE EXTRA
View a full list of keywords and
reserved words in JavaScript. 

4.All variables are case sensitive,
so score and Score would be
different variable names, but
it is bad practice to create two
variables that have the same
name using different cases.

5.Use a name that describes the
kind of information that the
variable stores. For example,
fi rstName might be used to
store a person's first name,
la st Name for their last name,
and age for their age.

6.If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.
For example, f i rstName rather
than fi rstnarne (this is referred
to as camel case). You can also
use an underscore between each
word (you cannot use a dash).
