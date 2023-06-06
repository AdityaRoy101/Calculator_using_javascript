# Calculator_using_javascript
A simple calculator using JavaScript for Beginners in JavaScript

# Code
---------
var a = prompt("Enter the first number");
var b = prompt("Enter the second number");
var c = prompt("Enter the operation you want to perform");
var a1 = Number(a);
var a2 = Number(b);
if(c === "+")
    alert("The sum of the number are : " + (a1 + a2));
else if(c === "*")
    alert("The multiplication of the numbers are : " + (a1 * a2));
else if(c === "-")
    alert("The substraction of the numbers are : " + (a1 - a2));
else if(c === "/")
    alert("The division of the two numbers are : " + (a1 / a2));
else
    alert("Wrong Choice");
