## 1. What is a Variable?
  **A variable is a named container that holds data values. Variables are essential in programming as they allow you to store, 
  modify, and retrieve information. In JavaScript, variables can hold various types of data, including numbers, strings, objects, 
  arrays, and more.**

## 2. Declaring Variables In JavaScript, you can declare a variable using three keywords: var, let, and const. Each has its own scope and usage:

- Var:
    Oldest way to declare a variable.
    Function-scoped: it is available within the function it is declared in.
    Can be re-declared and updated.
  
  ``` JavaScript
  var name = "Alice";
  console.log(name); // Output: Alice
  
- let:
    Introduced in ES6 (ECMAScript 2015).
    Block-scoped: it is available only within the block it is declared in (e.g., inside loops, conditionals).
    Can be updated but not re-declared in the same scope.

  ```JavaScript
  let age = 25;
  if (true) {
  let age = 30; // This age is block-scoped
  console.log(age); // Output: 30
  }
  console.log(age); // Output: 25
  
- const:
    Also introduced in ES6.
    Block-scoped like let.
    Must be initialized at the time of declaration and cannot be updated or re-declared.

  ```JavaScript
  const PI = 3.14;
  console.log(PI); // Output: 3.14
  // PI = 3.14159; // Error: Assignment to constant variable.

**Note:** Global Variable: _Variables can be defined in JavaScript without the previous words, meaning directly, as in the following example:_
```JavaScript
age = 34;
console.log(age); //Output: 34

