---
Title: "grid-template-rows"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Grids"
  - "Layout"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

A property that specifies the row structure of a grid container.

## Syntax

```css
.grid-container {
  display: grid;
  grid-template-rows: <row-space> <row-space>;
}
```

where `<row-space>` can be one of the following:

- Grid keyword: `auto`, `minmax()`, `repeat()`
- Pixel value: `300px`
- Percent value: `25%`
- Fractional unit value: `1fr`

## Example 1

A div split into three sections (e.g. header, main, footer).

```css
.spam-container {
  display: grid;
  grid-template-rows: 15% 70% 15%; 
}

```

## Example 2

Six equally sized columns that utilize the available space:

```css
.eggs-container {
  display: grid;
  grid-template-rows: repeat(6,auto);
}
```
