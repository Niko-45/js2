JavaScript (JS): Condition and Function Concepts

JavaScript (JS) is a versatile, high-level programming language primarily used for creating interactive web pages. Two fundamental concepts in JavaScript are conditions and functions. Here's a breakdown of each:

## 1. Conditions in JavaScript
Conditions are used to control the flow of a program by executing specific blocks of code based on whether a statement is true or false.

Types of Conditional Statements
if statement: Executes a block of code if the condition is true.

let age = 18;
if (age >= 18) {
  console.log("You are an adult.");
}
if...else statement: Executes one block of code if the condition is true, otherwise executes another block.

let age = 16;
if (age >= 18) {
  console.log("You are an adult.");
} else {
  console.log("You are a minor.");
}
if...else if...else statement: Used to test multiple conditions.


let score = 85;
if (score >= 90) {
  console.log("Grade: A");
} else if (score >= 80) {
  console.log("Grade: B");
} else if (score >= 70) {
  console.log("Grade: C");
} else {
  console.log("Grade: F");
}
Switch statement: Tests a value against multiple possible cases.


let day = 'Monday';
switch (day) {
  case 'Monday':
    console.log('Start of the work week.');
    break;
  case 'Friday':
    console.log('Weekend is near!');
    break;
  case 'Saturday':
  case 'Sunday':
    console.log('It’s the weekend!');
    break;
  default:
    console.log('Midweek days.');
}
Logical Operators Used in Conditions
AND (&&): Both conditions must be true.
OR (||): At least one condition must be true.
NOT (!): Reverses the condition's value (true becomes false, false becomes true).
Example:


let age = 20;
if (age >= 18 && age <= 65) {
  console.log("You are of working age.");
}
### 2. Functions in JavaScript
A function is a reusable block of code designed to perform a specific task. Functions allow you to organize, reuse, and maintain your code more efficiently.

Types of Functions
Function Declaration: Uses the function keyword and can be called before it is defined.

function greet(name) {
  return `Hello, ${name}!`;
}
console.log(greet('Alice')); // Hello, Alice!
Function Expression: Assigned to a variable, and the function can only be called after its definition.


const greet = function(name) {
  return `Hello, ${name}!`;
};
console.log(greet('Bob')); // Hello, Bob!
Arrow Function (ES6): A more concise syntax for writing functions.

const greet = (name) => `Hello, ${name}!`;
console.log(greet('Charlie')); // Hello, Charlie!
Anonymous Function: A function without a name, typically used as a callback.


setTimeout(function() {
  console.log('This runs after 3 seconds');
}, 3000);
Immediately Invoked Function Expression (IIFE): A function that runs as soon as it is defined.


(function() {
  console.log('This is an IIFE');
})();
![](https://miro.medium.com/v2/resize:fit:1400/1*oTlqfS_eCRt14QaAw7XpRw.jpeg)
