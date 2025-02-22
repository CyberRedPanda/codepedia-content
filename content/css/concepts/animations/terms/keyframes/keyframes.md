---
Title: "@keyframes"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Animation"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-css"
  - "https://www.codecademy.com/learn/paths/front-end-engineer-career-path"
  - "https://www.codecademy.com/learn/paths/full-stack-engineer-career-path"
---

## Definition

Controls an animation with multiple intermediate steps, defining the values of the properties at each keyframe.

## Syntax

```css
@keyframes animation-name {
  <keyframe-selector> {
    <keyframe-declaration>
  }
  <keyframe-selector> {
    <keyframe-declaration>
  }
}
```

- `<keyframe-selector>`: The selector for the element(s) to which the keyframe declaration should be applied.
- `<keyframe-declaration>`: The declaration block of the keyframe, made up of the property/value pairs.

**NOTE:** if you are only defining two keyframes, you can use the keywords `from` and `to` which are the same as `0%` and `100%` respectively for the `<keyframe-selector>`. Further customization on the `animation` property allows you to specify how many times an animation should play, duration of animation, change the direction of an animation, and much more.  


## Example 1

Run the keyframes rule `fade` for a duration of two seconds:

```css
div {
  height: 200px;
  width: 200px;
  background-color: black;
  animation-duration: 2s;
  animation-name: fade;
}

@keyframes fade {
  from {
    background-color: black;
  }
  to {
    background-color: white;
  }
}
```

## Example 2

Run the keyframes rule `fadeoutfadein` for a duration of two seconds:

```css
div {
  height: 200px;
  width: 200px;
  background-color: black;
  animation-duration: 4s;
  animation-name: fadeoutfadein;
}

@keyframes fadeoutfadein {
  0% {
    background-color: black;
  }
  20% {
    background-color: white;
  }
  40% {
    background-color: black;
  }
  60% {
    background-color: black;
  }
  80% {
    background-color: white;
  }
  100% {
    background-color: black;
  }
}
```

