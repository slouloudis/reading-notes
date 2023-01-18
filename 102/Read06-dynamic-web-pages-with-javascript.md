# Read: 06 - Dynamic web pages with JavaScript

## Hello, world!

JavaScript (unrelated to Java) is a programming language that is compiled at run time on your computer (or the users!) that also allows you to pass functions as an argument to other functions, return a function *from* a function, or be assigned to a variable. 

It can be used inside web browsers, servers, and more (although client-side and server-side are more relevant to us)

It supports multiple programming styles (oop-imperative-declarative)

[MDN JS Ref here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)



### JS is used in three major ways 

- The language itself
- DOM Api
- Server API (like node.JS)

API - broadly speaking, having two programs talk to each other. 

## Some Input/Output functions

---- **Outputs** ----

`alert("Hello world!");` - Creates a popup

`document.write("<h1> Hello World</h1>");` - Writes some html into your browser. Doesn't change source files. 


---- **Inputs**  ----

`var name = prompt("Please enter an input", ");`

`cofirm()` = function that allows the dev to ask a true/false question. It shows a popup asking the user to make sure. Like when you need to confirm to delete something. 

## Methods and Functions

A method is bound to an object like `console.log` - console being a variable, log being the method - we can pass an argument to it with `("")`

A function is similar to a method, but it doesn't need a variable with it - like `alert("hello!")`

    random knowledge alert is an alias for window.alert


Use `console.log("");` to print out data. 


## Variables

Think of variables as a box to store data.
It could be a value, like float or int, binary, or a string. 

    Remember! `=` means assignment, not "equal to" which is `==`

You can declare many variables in one statement, and you don't have to assign a value to a variable 

There are three ways to declare variables in JavaScript, although they share a basic format: 

`keyword variableName = data;`

The 3 keywords are as follows:-

- **var** - a variable - try not to use it. 
- **const** - declairs local constant (variable can't be changed)
- **let** - declares a local variable. 

### Scope

___

**Scope** determines what code can use what variables. Generally, local variables can only be accessed from {code blocks inside curly braces}


### So what's a computer anyway?

A computer needs to do the following:


- Take an input
- Store Information
- Process
- Output

Algorithm - a series of commands.

Output depends on what the computer is designed to do. 
