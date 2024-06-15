# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

1. Normal State : ![alt text](<result/Screenshot 2024-06-16 003307.png>)

2. Mouse Hovered Above Buttons :  ![alt text](<result/Screenshot 2024-06-16 003313.png>)

### Links

- Solution URL: [Add solution URL here](https://github.com/Yuvraj-H3R3/Yuvraj-H3R3.github.io.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Vanilla Javascript

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div>
  <div onmouseover="chbg(0)" onmouseout="revbg(0)" class="button">GitHub <br></div>
  <div onmouseover="chbg(1)" onmouseout="revbg(1)" class="button">Frontend Mentor <br></div>
  <div onmouseover="chbg(2)" onmouseout="revbg(2)" class="button">LinkedIn <br></div>
  <div onmouseover="chbg(3)" onmouseout="revbg(3)" class="button">Twitter <br></div>
  <div onmouseover="chbg(4)" onmouseout="revbg(4)" class="button">Instagram <br></div>
</div>
```
```js
let element = document.getElementsByClassName('button');
    var i;
    function chbg(i) {
      element[i].style.backgroundColor = "hsl(75, 94%, 57%)";
      element[i].style.color = 'hsl(0, 0%, 12%)';

    }

    function revbg(j) {
      element[j].style.backgroundColor = "hsl(0, 0%, 20%)";
      element[j].style.color = 'white';
    }
```

