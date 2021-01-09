Chapter 4: Links

Links its a feature in HTML page that's link the HTML page together.

● Links from one website to another. 
● Links from one page to another on the same website. 
● Links from one part of a web page to another part of the
same page. 
● Links that open in a new browser window. 
● Links that start up your email program and address a new 
email to someone.

Syntax:
<a href = "Link" > Link Name <\a>

- If I want to linking a page within my web page, it's best to use relative links rather than qualified URLs.

- I can create links to open email programs with an email address.


Chapter 15: Layout

- we used layout to control where each element sits on a page and how to create attractive web page: 

1- Bulding Blocks (we have level block element such as "<h1> <p> <ul> <li>" and in line element such as <img> <b> <i>). 
2- Containing elements (it's take a groups of elements in tag called <div>). 
3- controls the positions of elements (have five types: (1- relative. 2- normal. 3- absolute. 4- fixed. 5- floating.).
4- The float property moves content to the left or right of the page and can be used to create multi-column layouts.

- Grids help create a professional and flexible designs. 
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.

Chapter 3 - Functions, Methods and Objects: 

1- Functions: group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can reuse the function rather than repeating the same set of statements.  

Syntax of function :

function fun-name (parameters) 
{
Statements;
Return statement;
} 

Syntax of calling function:

function_name(parameters values) ; 

We have two types to declare the function:

1- FUNCTION DECLARATION:

A function declaration creates a function that you can call later in your code.

Example:

function area (width, height) 
return width * height; 
}; 
var size= area (3, 4) ; 

2- FUNCTION EXPRESSION:

If you put a function where the interpreter would expect to see an expression, then it is treated as an expression. 

Example:

var area = f unction(width, height) { 
return width * height; 
} ; 
var size = area (3, 4) ;  

2- Anonymous Function: function without name. 

Syntax:

Var variable = (function () 
{} ()) ;

- Variable Scoop:

The location where you declare a variable will affect where it can be used 
within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope. 


Pair Programing: 

- We use the pair programing to work more than one person on the same project:

1- Driver: programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. 

2- Navigator: uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code. 

Six reasons why we using pair programming:

* Greater efficiency. 
* Engaged collaboration. 
* Learning from fellow students. 
* Social Skills. 
* Job interview readiness.
* Work environment readness.
