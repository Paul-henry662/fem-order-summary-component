# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [Add live site URL here](https://paul-henry662.github.io/fem-order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- Sass / Scss
- BEM
- SMACSS file architecture

### What I learned

I think I managed the modules quite well, the card and button styles are reusable. Also, I learned 
about min() and max() and used it to set the behaviour of the card when shrinking the window:

```css
.card{
    width: max(90%, 120px);
    max-width: 350px;
}
```

## Author

- Frontend Mentor - [@Paul-henry662](https://www.frontendmentor.io/profile/Paul-henry662)


