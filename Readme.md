# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

1. Normal State :![alt text](<result/Screenshot 2024-06-12 212214.png>)


2. Active State : The Box-Shadow increases slightly and text is highlighted![alt text](<result/Screenshot 2024-06-12 212225.png>)


### Links

- Solution URL: [Solution Code](https://github.com/Yuvraj-H3R3/Yuvraj-H3R3.github.io.git)
- Live Site URL: [Live Solution](https://yuvraj-h3r3.github.io)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The best thing I learned is the few limitaion of CSS and it's solution using jacascript DOM properties. 

```html
<div onmouseover="chbg()" onmouseout="chbg1()" id="headText">HTML & CSS foundations <br></div>
```
```js
function chbg(){
  let element = document.getElementById('mainBox');
  element.style.boxShadow = '12px 12px black';
}

function chbg1(){
  let element = document.getElementById('mainBox');
  element.style.boxShadow = '9px 9px black';
}
```

### Continued development

Responsiveness and Utilizing Javascript is what I would like to continue in Future 

