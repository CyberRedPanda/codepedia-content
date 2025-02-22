---
Title: "<button>"
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Tags"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-html"
  - "https://www.codecademy.com/learn/paths/web-development"
---

## Definition 

Represents a button meant to be clicked by the user. While buttons are often associated with form submission, they can be used for any part of the page which needs a simple interface for user interaction.

## Syntax

```html
<button>
  <!-- Button content lives here -->
</button>
``` 

`<button>` is a tag that wraps around a block of HTML. By default it appears inline, like a `<span>` tag, and is styled to appear consistent with buttons on the device it is viewed on. 

It is possible for the content to be simple text, or other HTML elements. This can include lists, paragraphs, or even images.

## Attributes

There are a large number of available attributes that provide extra meaning to the browser. Listed below are a few of the common ones:

- `autofocus` will make the button automatically focused on the page.
- `disabled` will make the button unusable.
- `type` sets the intended behavior of the button, with common values below:
  - `submit`: This button should submit the form it is a part of.
  - `reset`: This button should reset the values in the form it is a part of.
  - `button`: This button should neither submit nor reset the form it is a part of.

## Example

Suppose there is a form that needs both a submit and reset button, and that the submit button should have an image rather than text. It might be coded in the following way:

```html
<html>
  <head>
  </head>
  <body>
    <form>
      <label>Your Name</label>
      <input type="text" name="user_name">
      <!-- More form elements -->
      <button type="reset">Reset Form</button>
      <button type="submit"><img src="submit.png" alt="Submit Form"></button>
    </form>
  </body>
</html>
```
