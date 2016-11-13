# Exam: HTML & CSS
Time needed: ~120 minutes   
100% is 16 points

### Getting Started
 - Fork this repository under your own account
 - Commit your progress frequently and with descriptive commit messages
 - All your answers and solutions should go in this repository

### What can I use?
 - You can use any resource online, but **please work individually**
 - **Don't just copy-paste** your answers and solutions, use your own words instead.


# Tasks

## 1. Build a design (~90 minutes) [10 points]
Build the following profile cards according to the design provided.   
Follow the design as closely as possible.   
Commit an HTML and a CSS file to this repository.
![design](task-1.png)

### Assets
John Duck | Jane Duck | Pencil icon
--------- | --------- | -----------
![duck](duck.jpg) | ![duck](duck2.jpg) | ![pencil-icon](edit-icon.png)   

### Other data
  - Name font size: 22 pixels
  - Text size: 14 pixels
  - Font family: Arial, sans-serif

### Acceptance criteria
The task is accepted if:
  - The result follows design [2p]
  - The code follows [style guide](https://github.com/greenfox-academy/teaching-materials/blob/master/styleguide/html-css.md) [1p]
  - The CSS & HTML are [valid](https://validator.w3.org/) [1p]
  - The HTML considers semantic responsibilities [2p]
  - The CSS avoids code duplication [2p]
  - The CSS has meaningful and short selectors [2p]

Extra points for if:
  - the result is centered on the page both vertically and horizontally [2p]


## 2. Understand code (~15 minutes) [2 points]
Read the following code snippet:   
**Question:** What is the height of the yellow and the blue box? and Why? Give a detailed explanation below!   
Add your answer to this readme file, commit your changes to this repository.
```HTML
<!DOCTYPE html>
<html>
  <head>
    <style>
      .foo {
        background: blue;
        overflow: hidden;
      }
      .baz {
        height: 100px;
        width: 50px;
        background: green;
      }
      .bar {
        float: left;
        width: 30px;
        height: 150px;
        background: yellow;
      }
    </style>
  </head>
  <body>
    <div class="foo">
      <div class="bar"></div>
      <div class="baz"></div>
    </div>
  </body>
</html>
```
#### Your answer: [2p]


## 3. Explain concepts (~15 minutes) [4 points]
Add your answer to this readme file, commit your changes to this repository.


### What is the CSS Box Model? What happens if you set an element's `box-sizing` property to `border-box`?
#### Your answer: [2p]


### What is the difference in semantics between an `<a>` (anchor) and a `<button>` element? Name one good example of using a `<button>`.
#### Your answer: [2p]
