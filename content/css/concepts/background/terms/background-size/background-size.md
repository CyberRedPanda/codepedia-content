---
Title: "background-size"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Background"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

Defines the size of one or more background images.

## Syntax

```css
background-size: <value>;
```

where `<value>` can be one of the following: 

- `contain`: scales the image as much as possible while keeping the aspect ratio and avoids clipping the image.
- `cover`: scales the image and maintains its aspect ratio, but this time the image will fill the whole area of the element and some clipping may occur.
- `auto`: tells the browser to automatically calculate the size based on the actual size of the image and the aspect ratio.
- Length value: `50%`, `100px 50px`

**Note:** If one length value is provided that will be applied to the width. If two length values are provided, the second value will be applied to the height.

## Example 1

Set background horizontal size to `500px`:

```css
.hero {
  background-image: url("fish.png");
  background-repeat: no-repeat;
  height: 1000px;
  background-size: 500px;
}
```

## Example 2

Set background horizontal size and vertical size with a % value:

```css
.hero {
  background-image: url("fish.png");
  background-repeat: no-repeat;
  height: 1000px;
  background-size: 50% 25%;
}
```

## Example 3

Set the background size to fill the whole element while maintaining aspect ratio:

```css
.hero {
  background-image: url("fish.png");
  background-repeat: no-repeat;
  height: 1000px;
  background-size: cover;
}
```

## Example 4

Set the background size to keep aspect ratio and avoid any clipping:

```css
.hero {
  background-image: url("fish.png");
  background-repeat: no-repeat;
  height: 1000px;
  background-size: contain;
}
```
