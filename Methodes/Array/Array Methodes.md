# Array Methodes:

- **`push(element)`**:
  Adds one or more elements to the end of an array.
  <br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  arr.push(4);
  console.log(arr); // [1, 2, 3, 4]

  ```
- **`pop()`**:Removes the last element from an array and returns that element.
  <br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  arr.pop();
  console.log(arr); // [1, 2]

  ```
- **`shift()`**:Removes the first element from an array and returns that element.
  <br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  arr.shift();
  console.log(arr); // [2, 3]

  ```
- **`unshift(element)`**:Adds one or more elements to the beginning of an array.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  arr.unshift(0);
  console.log(arr); // [0, 1, 2, 3]

  ```
- **`splice(start, deleteCount, item1, item2, ...)`**:Changes the contents of an array by removing or replacing existing elements.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  arr.splice(1, 2, 5); // Remove 2 elements from index 1 and add 5
  console.log(arr); // [1, 5, 4]

  ```
- **`slice(start, end)`**:Returns a shallow copy of a portion of an array.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  console.log(arr.slice(1, 3)); // [2, 3]

  ```
- **`forEach(callback, thisArg)`**:Executes a provided function once for each array element.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  arr.forEach((element) => console.log(element)); // 1, 2, 3

  ```
- **`map(callback, thisArg)`**:Creates a new array populated with the results of calling a provided function on every element in the calling array.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  let doubled = arr.map((num) => num * 2);
  console.log(doubled); // [2, 4, 6]

  ```
- **`filter(callback, thisArg)`**:Creates a new array with all elements that pass the test implemented by the provided function.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  let even = arr.filter((num) => num % 2 === 0);
  console.log(even); // [2, 4]

  ```
- **`reduce(callback, initialValue)`**:Executes a reducer function on each element of the array, resulting in a single output value.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  let sum = arr.reduce((accumulator, current) => accumulator + current, 0);

  ```
- **`reduceRight(callback, initialValue)`**:Similar to reduce(), but processes the array elements from right to left.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  let sum = arr.reduceRight((accumulator, current) => accumulator + current, 0);
  console.log(sum); // 10

  ```
- **`find(callback, thisArg)`**:Returns the first element in the array that satisfies the provided testing function.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  let found = arr.find((num) => num > 2);
  console.log(found); // 3

  ```
- **`findIndex(callback, thisArg)`**:Returns the index of the first element in the array that satisfies the provided testing function.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  let index = arr.findIndex((num) => num > 2);
  console.log(index); // 2

  ```
- **`some(callback, thisArg)`**:Tests whether at least one element in the array passes the test implemented by the provided function.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3, 4];
  let hasEven = arr.some((num) => num % 2 === 0);
  console.log(hasEven); // true

  ```
- **`every(callback, thisArg)`**:Tests whether all elements in the array pass the test implemented by the provided function.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [2, 4, 6];
  let allEven = arr.every((num) => num % 2 === 0);
  console.log(allEven); // true

  ```
- **`sort(compareFunction)`**:Sorts the elements of an array in place and returns the sorted array.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [3, 1, 4, 1, 5];
  arr.sort((a, b) => a - b);
  console.log(arr); // [1, 1, 3, 4, 5]

  ```
- **`reverse()`**:Reverses the order of the elements in an array.
<br><br>
  <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  arr.reverse();
  console.log(arr); // [3, 2, 1]

  ```
- **`join(separator)`**:Joins all elements of an array into a string and returns this string.
<br><br>
    <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  console.log(arr.join(", ")); // "1, 2, 3"

  ```
- **`concat(array2, array3, ..., arrayN)`**:Merges two or more arrays.
- **``**
  <br><br>
    <mark>Example:</mark>
  ```JavaScript
  let arr1 = [1, 2];
  let arr2 = [3, 4];
  let result = arr1.concat(arr2);
  console.log(result); // [1, 2, 3, 4]

  ```
- **`includes(searchElement, fromIndex)`**:Determines whether an array contains a certain element.
<br><br>
    <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  console.log(arr.includes(2)); // true
  console.log(arr.includes(4)); // false

  ```
- **`flat(depth)`**:Flattens an array up to the specified depth.
<br><br>
    <mark>Example:</mark>
  ```JavaScript
  let arr = [1, [2, [3, [4]]]];
  console.log(arr.flat(2)); // [1, 2, 3, [4]]

  ```
- **`flatMap(callback, thisArg)`**:First maps each element using a mapping function, then flattens the result into a new array.
<br><br>
    <mark>Example:</mark>
  ```JavaScript
  let arr = [1, 2, 3];
  let result = arr.flatMap((num) => [num, num * 2]);
  console.log(result); // [1, 2, 2, 4, 3, 6]

  ```

<hr>

# JavaScript Array Methods

| Method                             | Description                                                                        | Example                                                                                   |
|------------------------------------|------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| **`push(element)`**                | Adds one or more elements to the end of an array.                                  | `let arr = [1, 2, 3]; arr.push(4); console.log(arr); // [1, 2, 3, 4]`                     |
| **`pop()`**                        | Removes the last element from an array and returns that element.                   | `let arr = [1, 2, 3]; arr.pop(); console.log(arr); // [1, 2]`                             |
| **`shift()`**                      | Removes the first element from an array and returns that element.                  | `let arr = [1, 2, 3]; arr.shift(); console.log(arr); // [2, 3]`                           |
| **`unshift(element)`**             | Adds one or more elements to the beginning of an array.                            | `let arr = [2, 3]; arr.unshift(1); console.log(arr); // [1, 2, 3]`                        |
| **`splice(start, deleteCount, ...)`**| Changes the contents of an array by removing or replacing elements.                | `let arr = [1, 2, 3, 4]; arr.splice(1, 2, 'a', 'b'); console.log(arr); // [1, 'a', 'b', 4]`|
| **`slice(start, end)`**            | Returns a shallow copy of a portion of an array.                                   | `let arr = [1, 2, 3, 4]; let sliced = arr.slice(1, 3); console.log(sliced); // [2, 3]`    |
| **`forEach(callback)`**            | Executes a provided function once for each array element.                         | `let arr = [1, 2, 3]; arr.forEach(num => console.log(num * 2));`                          |
| **`map(callback)`**                | Creates a new array with the results of calling a function for every array element.| `let arr = [1, 2, 3]; let doubled = arr.map(num => num * 2); console.log(doubled);`       |
| **`filter(callback)`**             | Creates a new array with all elements that pass the test implemented by a function.| `let arr = [1, 2, 3, 4]; let even = arr.filter(num => num % 2 === 0); console.log(even);` |
| **`reduce(callback, initialValue)`**| Reduces the array to a single value by executing a function on each element.       | `let arr = [1, 2, 3]; let sum = arr.reduce((a, b) => a + b, 0); console.log(sum);`         |
| **`reduceRight(callback, ...)`**   | Similar to `reduce()`, but processes the array from right to left.                 | `let arr = [1, 2, 3]; let sum = arr.reduceRight((a, b) => a + b, 0); console.log(sum);`    |
| **`find(callback)`**               | Returns the first element in the array that satisfies the provided function.       | `let arr = [1, 2, 3]; let found = arr.find(num => num > 2); console.log(found);`          |
| **`findIndex(callback)`**          | Returns the index of the first element that satisfies the provided function.       | `let arr = [1, 2, 3]; let index = arr.findIndex(num => num > 2); console.log(index);`      |
| **`some(callback)`**               | Tests if at least one element in the array passes the test implemented by a function.| `let arr = [1, 2, 3]; let hasEven = arr.some(num => num % 2 === 0); console.log(hasEven);`|
| **`every(callback)`**              | Tests whether all elements in the array pass the test implemented by a function.   | `let arr = [2, 4, 6]; let allEven = arr.every(num => num % 2 === 0); console.log(allEven);`|
| **`sort(compareFunction)`**        | Sorts the elements of an array in place and returns the sorted array.              | `let arr = [3, 1, 4]; arr.sort((a, b) => a - b); console.log(arr);`                       |
| **`reverse()`**                    | Reverses the order of the elements in an array.                                    | `let arr = [1, 2, 3]; arr.reverse(); console.log(arr); // [3, 2, 1]`                      |
| **`join(separator)`**              | Joins all elements of an array into a string.                                      | `let arr = [1, 2, 3]; console.log(arr.join(', ')); // "1, 2, 3"`                          |
| **`concat(array2, ...)`**          | Merges two or more arrays.                                                        | `let arr1 = [1, 2]; let arr2 = [3, 4]; let merged = arr1.concat(arr2); console.log(merged);`|
| **`includes(searchElement)`**      | Determines whether an array contains a certain element.                           | `let arr = [1, 2, 3]; console.log(arr.includes(2)); // true`                              |
| **`flat(depth)`**                  | Flattens an array up to the specified depth.                                       | `let arr = [1, [2, [3]]]; console.log(arr.flat(2)); // [1, 2, 3]`                         |
| **`flatMap(callback)`**            | Maps each element using a function, then flattens the result into a new array.     | `let arr = [1, 2]; let result = arr.flatMap(num => [num, num * 2]); console.log(result);`  |
