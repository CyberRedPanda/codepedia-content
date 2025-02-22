---
Title: ".unshift()"
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

Adds one or more elements to beginning of array and returns new length.

## Syntax

```js
array.unshift(item1, item2, ...);
```

## Examples

To add the element `'Monday'` to the `daysOfWeek` array:

```js
const daysOfWeek = ['Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday'];

daysOfWeek.unshift('Monday');

console.log(daysOfWeek);
// Output: ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday']
```

To add elements `1` and `2` to the `countToTen` array:

```js
const countToTen = [3, 4, 5, 6, 7, 8, 9, 10];

countToTen.unshift(1, 2);

console.log(countToTen);
// Output: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```
