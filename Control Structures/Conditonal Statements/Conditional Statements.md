# Conditional Statements:
**Conditional statements are used to perform different actions based on different conditions. In JavaScript, the most common conditional statements are:**
1. **`if` Statement:**<br>
   The `if` statement executes a block of code only if the specified condition evaluates to true.<br><br>
   <mark>Syntax:</mark>
    ```JavaScript
   if (condition) {
    // code to be executed if the condition is true
    }
    ```
    <mark>Example:</mark>
    ```JavaScript
    let age = 18;
    if (age >= 18) {
    console.log("You are an adult.");
    }


   
2. **`if...else` Statement:**<br>The else block is executed if the if condition evaluates to false.<br><br>
   <mark>Syntax:</mark>
   ```JavaScript
   if (condition) {
    // code to be executed if the condition is true
    } else {
    // code to be executed if the condition is false
    }
   ```
   <mark>Example:</mark>
   ```JavaScript
   let age = 16;
   if (age >= 18) {
    console.log("You are an adult.");
    } else {
    console.log("You are not an adult.");
    }

   
3. **`else if` Statement:**<br>
You can test multiple conditions using `else if` blocks. The first condition that evaluates to true will execute its block of code.<br><br>
<mark>Syntax:</mark>
    ```JavaScript
    if (condition1) {
    // code to be executed if condition1 is true
    } else if (condition2) {
    // code to be executed if condition2 is true
    } else {
    // code to be executed if both conditions are false
    }
    ```

    <mark>Example:</mark>
    ```JavaScript
    let score = 85;
    if (score >= 90) {
    console.log("Grade: A");
    } else if (score >= 80) {
    console.log("Grade: B");
    } else {
    console.log("Grade: C");
    }
    ```
4. **`switch` Statement:**<br>
The switch statement is used to perform different actions based on different values of a variable. It is an alternative to multiple `if...else` if conditions.<br><br>
<mark>Syntax:</mark>
    ```JavaScript
    switch (expression) {
      case value1:
        // code to be executed if expression === value1
          break;
      case value2:
        // code to be executed if expression === value2
          break;
      default:
        // code to be executed if no case matches
    }
    ```
    <mark>Example:</mark>
    ```JavaScript
    let day = 3;
    switch (day) {
      case 1:
          console.log("Monday");
        break;
      case 2:
          console.log("Tuesday");
        break;
      case 3:
          console.log("Wednesday");
        break;
      default:
        console.log("Invalid day");
    }

