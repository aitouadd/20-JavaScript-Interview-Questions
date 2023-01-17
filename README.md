# 20-JavaScript-Interview-Questions

***1 - What is JavaScript?***


JavaScript is a dynamic programming language that's used for web development, in web applications, for game development, and lots more. It allows you to implement dynamic features on web pages that cannot be done with only HTML and CSS


***2 - What is the difference between JavaScript and ECMAScript?***

JavaScript is a general-purpose scripting language that conforms to the ECMAScript specification. ***The ECMAScript*** specification is a blueprint for creating a scripting language. JavaScript is an implementation of that blueprint. On the whole, JavaScript implements the ECMAScript specification as described in ECMA-262.

***3 - What is a variable in JavaScript and what are the different types of variables?***

Variables can be used to store data in a program, such as strings, numbers, JSON objects, or boolean values. In JavaScript, there are three different variable types: var , let , and const .

***4 - What are the different data types in JavaScript?***

In Javascript, there are five basic, or primitive, types of data. The five most basic types of data are strings, numbers, booleans, undefined, and null.


***5 - What is an object in JavaScript and how do you create one?***

In JavaScript, an object can be created in two ways: 1) using Object Literal/Initializer Syntax
2) using the Object() Constructor function with the new keyword.
Objects created using any of these methods are the same.


***6 - What is a function in JavaScript and how do you create one?***

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses (). Function names can contain letters, digits, underscores, and dollar signs (same rules as variables). The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)

***7 - What is an event in JavaScript and how do you handle them?***

What is an Event ? JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. When the user clicks a button, that click too is an event.


***8 - What is a closure in JavaScript and how do they work?***

A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function.

***9 - What is the difference between null and undefined in JavaScript?***

Null: It is the intentional absence of the value. It is one of the primitive values of JavaScript.
Undefined: It means the value does not exist in the compiler.

***10 - What is the difference between == and === in JavaScript?***

The main difference between the == and === operator in javascript is that the == operator does the type conversion of the operands before comparison, whereas the === operator compares the values as well as the data types of the operands


***11 - What is the difference between var, let, and const in JavaScript?***

var is function-scoped while let and const are block-scoped. var variables can be reassigned while let and const variables can not. var variables are declared using the var keyword while let and const variables are declared using the let and const keywords respectively


***12 - What is the difference between a for loop and a for-in loop in JavaScript?***

Loops are used to execute the same block of code again and again, as long as a certain condition is met. The basic idea behind a loop is to automate the repetitive tasks within a program to save the time and effort. JavaScript now supports five different types of loops:

while — loops through a block of code as long as the condition specified evaluates to true.
do…while — loops through a block of code once; then the condition is evaluated. If the condition is true, the statement is repeated as long as the specified condition is true.

for — loops through a block of code until the counter reaches a specified number.

for…in — loops through the properties of an object.





***13 - What is the difference between a for-of loop and a for-in loop in JavaScript?***


for…in — loops through the properties of an object.
for…of — loops over iterable objects such as arrays, strings, etc.



***14 - What is an arrow function in JavaScript and how do you use it?***

An arrow function expression is an anonymous function expression written with the “fat arrow” syntax ( => ). Like traditional function expressions, arrow functions are not hoisted, and so you cannot call them before you declare them. They are also always anonymous—there is no way to name an arrow function



***15 - What is the difference between call and apply in JavaScript?***

The Difference Between call() and apply()
The difference is: The call() method takes arguments separately. The apply() method takes arguments as an array. The apply() method is very handy if you want to use an array instead of an argument list.


***16 - What is the difference between bind and call in JavaScript?***

***Summary***. call : binds the this value, invokes the function, and allows you to pass a list of arguments. apply : binds the this value, invokes the function, and allows you to pass arguments as an array. bind : binds the this value, returns a new function, and allows you to pass in a list of arguments.


***17 - What is the difference between a class and an object in JavaScript?***

A class defines object properties including a valid range of values, and a default value. A class also describes object behavior. An object is a member or an "instance" of a class. An object has a state in which all of its properties have values that you either explicitly define or that are defined by default settings.



***18 - What is the prototype in JavaScript and how do you use it?***

A prototype is an existing inbuilt functionality in JavaScript. Whenever we create a JavaScript function, JavaScript adds a prototype property to that function. A prototype is an object, where it can add new variables and methods to the existing object.


***19 - What is a promise in JavaScript and how do you use it?***

A Promise is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason


***20 - What is a async/await in JavaScript and how do you use it?***

The async function declaration declares an async function where the await keyword is permitted within the function body. The async and await keywords enable asynchronous, promise-based behavior to be written in a cleaner style, avoiding the need to explicitly configure promise chains.
