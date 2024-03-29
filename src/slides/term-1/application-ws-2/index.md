---
title: Applicant Workshop Two
private: true
---

# Application workshops

## 2. Functions

---

<!-- {.primary} -->

### Introduction

---

A function can be defined as a set of instructions to complete a task

---

A function may take some input and return an output

---

```js
// Add all the numbers in the array
// and assign the result to a variable

// Find out how many numbers are in the array
// and assign that to a variable

// Divide the total by the length of the array
// and return the result
```

---

### The benefits of using functions

---

**Define reusable code**

Declare code which can be used more than once with different inputs to give different outputs

---

**Modularise our code**

Break our code up into sections based on its purpose

---

**Help us understand our code**

Having a well named function is easier to understand than a list of statements

A meaningful name makes it easier to understand what the function does. A function that adds two numbers can be “addTwoNumbers”

---

### Using functions

---

**Step one:** Declare the function

---

```js
function myNamedFunction(parameterOne, parameterTwo) {
  // What my function does
}
```

---

```js
function multiplyTwoNumbers(numOne, numTwo) {
  return numOne * numTwo;
}
```

---

**Step two:** Call the function

---

```js
myNamedFunction(argumentOne, argumentTwo);
```

---

## Parts of a function

---

These definitions are specific to named functions

---

**The function keyword**

Tells Javascript that we are declaring a function

---

**The function name**

Tells JavaScript how we will reference the function when we'd like to call it

---

**Round brackets**

_Declaring:_ Contain any parameters we'd like to pass in

_Calling:_ Contain any arguments we need to pass in

Commas separate each parameter or argument

---

**Parameters and arguments**

A parameter is like a variable defined in a function declaration

An argument is the actual value of this parameter that get passed when the function is called

---

**Curly brackets**

Define the function block

---

**Function body**

The body of a function refers to the statements inside the function (usually within curly brackets)

---

**Return keyword**

The `return` keyword ends function execution and gives back a value to the function caller

---

```js
function addTwoNumbers(num1, num2) {
  return num1 + num2;
}

let total = addTwoNumbers(2, 3);
console.log(total);
```

---

Nothing inside the curly brackets and after the return will run, as we break out of the block

---

```js
function addTwoNumbers(num1, num2) {
  return num1 + num2;
  console.log("This will not log");
}

let total = addTwoNumbers(2, 3);
```

---

## Customisable and structural

---

```js
function addTwoNumbers(num1, num2) {
  return num1 + num2;
}

let total = addTwoNumbers(2, 3);
console.log(total);
```

---

### Scope

---

Scope is the context in which a variable can be accessed

---

_Global variables_ are defined outside any function blocks and can be accessed anywhere

---

_Local variables_ are defined within a function block and can only be accessed within that function

---

```js
let myGlobalVariable = "Hello";

function stringMaker() {
  let myLocalVariable = "World";

  return myGlobalVariable + " " + myLocalVariable;
}

console.log(stringMaker()); // logs "Hello World"
console.log(myLocalVariable); // causes error
```

---

## Examples

---

**1. Write a function that can return the string “I am a function”.**

This function doesn’t need to be passed any arguments

Calling the function like this:

`talkToMe()`

should output

`I am a function`

---

**2. Write a function that accepts a number as an argument and returns double the number.**

For example, if I called the function like so

`doubleArg(23);`

should output

`46`

---

**3. Write a function that can take two numbers as arguments, and return the product of them**

For example, if you call the function like this:

`timesTwoNumbers(12, 2);`

should output

`24`

---

<!-- {.primary} -->

## Weekly prompts

formerly, _The daily challenge_

---

Each week, we'll post a set of prompts on Discord

---

Read `#-how-to` first to understand how to work on the tasks

---

`#weekly-prompts` is where we'll post the prompts

---

`#help-and-hints` is where you can ask for help or give help to others

---

We'll start with three this week and build up from there. The concepts you need for each set of prompts will be introduced in workshops!

---

<!-- {.primary} -->

## Approaching problems

A four-step approach

---

### 1. Understand the problem

What is it asking you to do? What are the inputs and outputs?

---

### 2. Write Pseudocode

Break the problem down into key steps

Use JavaScript Comments

---

```js
// Add all the numbers in the array
// and assign the result to a variable

// Find out how many numbers are in the array
// and assign that to a variable

// Divide the total by the length of the array
// and return the result
```

---

### 3. Write JavaScript

Following your pseudocode, code each step. Remember to `console.log()` to check your code along the way.

---

### 4. Refactor

What can you change about your code to make it more efficient? How might you solve the problem differently?
