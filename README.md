# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screen-shot.png)

### Links

- Solution URL: [Source code](https://github.com/asamoahe3/product-preveiw-card-component)
- Live Site URL: [Live preview](https://asamoahe3.github.io/product-preveiw-card-component/)

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
I have learn how to set dynamic images for diffrent screen sizes using html picture tag.

```html
  <picture>
      <source media="(min-width: 640px)" srcset="images/image-product-desktop.jpg">
      <source media="(max-width: 639px)" srcset="images/image-product-mobile.jpg">
      <img src="images/image-product-mobile.jpg" alt="">
    </picture>
```


## Author

- Frontend Mentor - [@asmoahe3](https://www.frontendmentor.io/profile/asamoahe3)
