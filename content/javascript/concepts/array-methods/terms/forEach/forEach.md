---
Title: ".forEach()"
Subjects:
  - "Web Development"
  - "Computer Science"
Tags:
  - "Arrays"
  - "Methods"
Catalog Content:
  - "https://www.codecademy.com/learn/introduction-to-javascript"
  - "https://www.codecademy.com/learn/paths/web-development"
---

## Definition

Loops over the array, passing each item in the array into the callback function provided.

## Syntax

```js
array.forEach((value, index, array) => {...});
```

A function can be invoked with three arguments: 

- `value`: The value of the array element.
- `index` (optional): The index of the array element.
- `array` (optional): The array itself.

**Note:** Unlike a regular `for` loop, `.forEach()` method does not provide a way to terminate iteration before all elements have been passed to the function.

## Example 1

Logging each value in an array:

```js
['a', 'b', 'c'].forEach((letter) => console.log(letter));
```

The output would be:

```
a
b
c
```

## Example 2

Finding the sum of an array:

```js
const values = [7, 17, 34, 41, 22, 5];
let sumOfValues = 0;

values.forEach((value) => (sumOfValues += value));

console.log(sumOfValues);
// Output: 126
```
