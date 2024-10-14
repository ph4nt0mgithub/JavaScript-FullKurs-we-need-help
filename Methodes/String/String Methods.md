# String Methods:
- **`toUpperCase()`**<br>
Converts the string to uppercase.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "hello";
    console.log(str.toUpperCase()); // "HELLO"

    ```
- **`toLowerCase()`**<br>
Converts the string to lowercase.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "HELLO";
    console.log(str.toLowerCase()); // "hello"

    ```
- **`trim()`**<br>
Removes whitespace from both ends of the string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "   Hello   ";
    console.log(str.trim()); // "Hello"

    ```
- **`slice(start, end)`**<br>
Extracts a section of a string and returns it as a new string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello, World!";
    console.log(str.slice(0, 5)); // "Hello"

    ```
- **`split(separator, limit)`**<br>
Splits a string into an array of substrings.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "a,b,c";
    console.log(str.split(",")); // ["a", "b", "c"]

    ```
- **`replace(searchValue, newValue)`**<br>
Replaces a specified value with another value in a string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello, World!";
    console.log(str.replace("World", "JavaScript")); // "Hello, JavaScript!"

    ```
- **`includes(searchString, position)`**<br>
Determines whether a string contains a specified substring.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello, World!";
    console.log(str.includes("World")); // true

    ```
- **`indexOf(searchValue, fromIndex)`**<br>
Returns the index of the first occurrence of a specified value in a string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello, World!";
    console.log(str.indexOf("o")); // 4

    ```

- **`lastIndexOf(searchValue, fromIndex)`**<br>
Returns the index of the last occurrence of a specified value in a string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello, World!";
    console.log(str.lastIndexOf("o")); // 8

    ```
- **`charAt(index)`**<br>
Returns the character at a specified index.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello";
    console.log(str.charAt(0)); // "H"

    ```
- **`charCodeAt(index)`**<br>
Returns the Unicode of the character at a specified index.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello";
    console.log(str.charCodeAt(0)); // 72

    ```
- **`substring(indexStart, indexEnd)`**<br>
Returns a substring from the string between two specified indices.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello, World!";
    console.log(str.substring(0, 5)); // "Hello"

    ```
- **`concat(string2, string3, ..., stringN)`**<br>
Combines two or more strings and returns a new string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str1 = "Hello";
    let str2 = "World";
    console.log(str1.concat(", ", str2)); // "Hello, World"

    ```
- **`repeat(count)`**<br>
Returns a new string which contains the specified number of copies of the original string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "abc";
    console.log(str.repeat(3)); // "abcabcabc"

    ```
- **`startsWith(searchString, position)`**<br>
Determines whether a string starts with the characters of a specified string.
<br><br>
<mark>Example:</mark>
  ```JavaScript
  let str = "Hello, World!";
  console.log(str.startsWith("Hello")); // true

  ```
- **`endsWith(searchString, length)`**<br>
Determines whether a string ends with the characters of a specified string.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "Hello, World!";
    console.log(str.endsWith("World!")); // true

    ```
- **`padStart(targetLength, padString)`**<br>
Pads the current string with another string (padString) until the resulting string reaches the given targetLength.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "5";
    console.log(str.padStart(2, "0")); // "05"

    ```
- **`padEnd(targetLength, padString)`**<br>
Pads the current string with another string (padString) until the resulting string reaches the given targetLength.
<br><br>
<mark>Example:</mark>
    ```JavaScript
    let str = "5";
    console.log(str.padEnd(2, "0")); // "50"

    ```
  
