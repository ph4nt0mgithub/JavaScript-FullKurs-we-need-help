# Number Methods:
- **`isNaN(value):`**<br>
  Determines whether the value is NaN (Not a Number).
  <br><br>
  <mark>Example:</mark>
  ```JavaScript
  console.log(Number.isNaN(NaN)); // true
  console.log(Number.isNaN(123)); // false

- **`isInterger(value):`**<br>
Determines whether the value is an integer.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  console.log(Number.isInteger(4)); // true
  console.log(Number.isInteger(4.5)); // false

- **`isSafeInteger(value):`**<br>
Determines whether the value is a safe integer.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  console.log(Number.isSafeInteger(9007199254740991)); // true
  console.log(Number.isSafeInteger(9007199254740992)); // false

- **`parseFloat(string):`**<br>
Parses a string argument and returns a floating-point number.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  console.log(Number.parseFloat("3.14")); // 3.14
  console.log(Number.parseFloat("10")); // 10

- **`parseInt(string, radix):`**<br>
Parses a string argument and returns an integer of the specified radix.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  console.log(Number.parseInt("10", 10)); // 10
  console.log(Number.parseInt("1010", 2)); // 10

- **`toFixed(digits):`**<br>
Formats a number using fixed-point notation.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let num = 2.34567;
  console.log(num.toFixed(2)); // "2.35"

- **`toString(radix):`**<br>
Converts a number to a string in the specified base.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let num = 15;
  console.log(num.toString(2)); // "1111"
  console.log(num.toString(16)); // "f"
