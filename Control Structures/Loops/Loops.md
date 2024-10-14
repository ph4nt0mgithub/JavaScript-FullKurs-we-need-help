# Loops:
**Loops are used to repeat a block of code multiple times, either a fixed number of times or until a condition is met. JavaScript offers several loop types:**

1.**`for` Loop:**
The `for` loop repeats a block of code a specified number of times.<br><br>
  <mark>Syntax:</mark>
  ```JavaScript
  for (initialization; condition; increment/decrement) {
    // code to be executed on each iteration
  }
  ```
  <mark>Example:</mark>
  ```JavaScript
  for (let i = 0; i < 5; i++) {
    console.log(i); // Prints 0 to 4
  }
  ```
2.**`while` Loop:**
The `while` loop repeats a block of code as long as a specified condition is true.<br><br>
<mark>Syntax:</mark>
```JavaScript
while (condition) {
    // code to be executed while the condition is true
}
```
<mark>Example:</mark>
```JavaScript
let i = 0;
while (i < 5) {
    console.log(i); // Prints 0 to 4
    i++;
}
```
3.**`do...while` Loop:**
The `do...while` loop is similar to the while loop, except that the code block will execute at least once, even if the condition is false.<br><br>
<mark>Syntax:</mark>
```JavaScript
do {
    // code to be executed
} while (condition);
```
<mark>Example:</mark>
```JavaScript
let i = 0;
do {
    console.log(i); // Prints 0 to 4
    i++;
} while (i < 5);
```
4.**`for...in` Loop:**
The `for...in` loop is used to iterate over the properties of an object.<br><br>
<mark>Syntax:</mark>
```JavaScript
for (let key in object) {
    // code to be executed for each key in the object
}
```
<mark>Example:</mark>
```JavaScript
let person = { name: "Alice", age: 25, city: "New York" };
for (let key in person) {
    console.log(key + ": " + person[key]);
}
// Output: name: Alice, age: 25, city: New York
```
5.**`for...of` Loop:**
The `for...of` loop is used to iterate over iterable objects like arrays, strings, etc.<br><br>
<mark>Syntax:</mark>
```JavaScript
for (let element of iterable) {
    // code to be executed for each element in the iterable
}
```
<mark>Example:</mark>
```JavaScript
let fruits = ["apple", "banana", "orange"];
for (let fruit of fruits) {
    console.log(fruit);
}
// Output: apple, banana, orange
