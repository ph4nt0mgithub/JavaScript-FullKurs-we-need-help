## Datatypes in JavaScript:
In JavaScript, datatypes are categorized into two main groups: Primitive and Non-Primitive types. Understanding these datatypes is crucial for effective programming, as they determine how data is stored, manipulated, and interacted with in your code.
<hr>

1. <mark>**Primitive Data Types:**</mark>
   - `Number`: <br>Represents both integer and floating-point numbers.
     - [x] Example:
           
           let age = 25;           // Integer
           let temperature = 36.6; // Floating-point number
           
   - `String`: <br>Represents a sequence of characters, enclosed in single quotes ('), double quotes ("), or backticks (`) for template literals.
      - [x] Example:

            let name = "Alice";      // Double quotes
            let greeting = 'Hello';  // Single quotes
            let message = `Hi, ${name}`; // Template literal

   - `Boolean`: <br>Represents a logical entity that can have two values: true or false.
       - [x] Example:

             let isStudent = true; // Boolean value
             
   - `Null`: <br>Represents an intentional absence of any value; it is a primitive value.
       - [x] Example:
    
             let y = null; // y is explicitly set to null

   - `Undefined`: <br>Indicates a variable that has been declared but has not been assigned a value.
       - [x] Example:

             let x; // x is undefined
 
   - `Symbol`: <br>Represents a unique and immutable identifier. Useful for object property keys to avoid name clashes.
       - [x] Example:

             const uniqueID = Symbol('id'); // Unique symbol

   - `BigInt`: <br>A special type that can represent whole numbers larger than Number.MAX_SAFE_INTEGER.
       - [x] Example:
             
             const bigNumber = 1234567890123456789012345678901234567890n; // BigInt

     
2.<mark> **Non-Primitive Data Types:**</mark>
   - `Object`: <br>A collection of key-value pairs. Objects can hold multiple values as properties.
       - [x] Example:

             let person = {
                name: "Alice",
                age: 25,
                isStudent: true
                }; // Object

   - `Array`: <br>A special type of object used to store ordered lists of values. Arrays can hold multiple values in a single variable.
       - [x] Example:

             let fruits = ["apple", "banana", "orange"]; // Array

   - `Function`: <br>Functions are a special type of object that can be called and executed. They can be assigned to variables, passed as arguments, and returned from other functions.
       - [x] Example:

             function greet(name) {
                return `Hello, ${name}!`;
              }

              let sayHello = greet; // Assigning function to a variable
              console.log(sayHello("Alice")); // "Hello, Alice!"


     <hr>

| Datatype      | Description                                        | Example                                           |
|---------------|----------------------------------------------------|---------------------------------------------------|
| **Number**    | Represents numeric values                          | `let age = 25;`                                   |
| **String**    | Represents textual data                            | `let name = "Alice";`                             |
| **Boolean**   | Represents true or false                          | `let isStudent = true;`                           |
| **Undefined** | A variable declared but not assigned a value     | `let x; // x is undefined`                        |
| **Null**      | Represents the intentional absence of value       | `let y = null;`                                  |
| **Symbol**    | Represents unique and immutable identifiers       | `const uniqueID = Symbol('id');`                 |
| **BigInt**    | Represents large integers                          | `const bigNumber = 1234567890123456789012345678901234567890n;` |
| **Object**    | A collection of key-value pairs                   | `let person = { name: "Alice", age: 25 };`      |
| **Array**     | An ordered list of values                         | `let fruits = ["apple", "banana", "orange"];`   |
| **Function**  | A callable object that can execute code           | `function greet(name) { return "Hello, " + name; }` |

