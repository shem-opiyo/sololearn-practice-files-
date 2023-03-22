# Documentation 

Sololearn Javascript
i.	Welcome to Javascript
-	Ever visit a website that made you think…"Hey, this website is really cool and interactive"? Well, JavaScript was probably making it happen....
-	In this course, we'll learn the basic concepts of JavaScript - one of the most popular programming languages that makes websites dynamic and interactive. With JavaScript, you can also create mobile apps and games, process data, and much more!
Output
-	Let's kick things off by creating a program that displays "Hello World!" to the console using the console.log() function.
-	The console is part of the web browser and allows you to log messages, run JavaScript code, and see errors and warnings.
Text
-	To use text in JavaScript, we need to enclose it in quotes.
-	You can use the console.log() function as many times as you want. Each statement outputs text from a new line:
console.log("Hello!");
console.log("My name is JavaScript");
console.log("Coding is an art");
Numbers 
-	When working with numbers quotes are not needed 
console.log(42);
ii.	JavaScript in HTML
-	You can add JavaScript code in an HTML document using the <script> tag. 
-	Do you remember the console.log() function from the previous lesson? Let's see how it's written in the HTML document:
<body>
    <script>
      console.log("JavaScript in HTML");
    </script>
</body>
iii.	Alert Box 
-	Another way to display messages is an alert box.
-	You can generate them by using the alert() function:
alert("I am an alert box");
iv.	Comments 
-	Comments are explanatory statements that you can include in a program to benefit the person reading your code.
-	A single-line comment starts with //:
// outputs a wish
console.log("Have a good day!");
-	You can also create multi-line comments. 
-	They start with /* and end with */, making everything in between a comment.

/* an important
reminder
for you */
console.log("Keep rocking!");
v.	Simple Operations
-	Let's talk about calculations! They are everywhere, including in programming. So, they will be in your future programs too! 
-	Performing a calculation in JavaScript is simple, just enter it into the console.log() function.
-	Just like in regular math, multiplication and division is calculated before addition and subtraction:
-	To control precedence, use parentheses to indicate the order in which you want to perform operations, like line four:
console.log(1 + 2);
console.log(6*3+2);
console.log(42/7);
console.log((5+2)*3);
vi.	Variables 
-	Variables are created using the let keyword. They are containers for storing values.
-	In the case below, name is the name of our variable.
-	After creating the variable we can give it a value. This is called initialization. In this case, the variable name has been initialized to James. The equal sign = is used to assign a value to our variable.
-	You can also assign your variable a value during the creation:
-	After initializing a variable, we can output its value using the console.lo(); function:
let name;
name = "James";
let message = “Message assigned during creation”;
console.log(name);
-	Variables can change their value during the program. That's why they are called variables 😀! Updating the value of a variable can be done as many times as needed.
let age = 17;
//after 1 year
age = 18;

console.log(age);
Constants
-	Constant can’t change their value throughout the program.
-	Declared using the const keyword
const color = 'red';
console.log(color);
color = 'yellow'; //this will result in error
-	
vii.	
