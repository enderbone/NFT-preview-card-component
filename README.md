# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: (https://github.com/enderbone/NFT-preview-card-component)
- Live Site URL: (https://enderbone.github.io/NFT-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

I learned how to use the z-index propriety and how to use a background-image and a background at the same time in css. I also learned (after much difficulty) how to use and manipulate the opacity of images for my own interest.

```css
.main-image-box {
    position: relative;
}

.image-main {
    width: 270px;
    height: 270px;
    margin: auto;
    position: sticky;
    background-image: url(images/image-equilibrium.jpg);
    background-position: center;
    background-size: contain;
    border-radius: 15px;

    z-index: 1;
}

.image-hover {
    width: 270px;
    height: 270px;
    margin: auto;
    position: absolute;
    background-image: url(images/icon-view.svg);
    background-color: var(--prim2OPACITY);
    background-repeat: no-repeat;
    background-position: center;
    opacity: 0;
    border-radius: 20px;

    top: 0px;
    z-index: 2;
    transition: 300ms ease;
}

.image-hover:hover {
    opacity: 1;
}
```

## Author

- Frontend Mentor - [@enderbone](https://www.frontendmentor.io/profile/enderbone)
- Discord - [@eberdone]
- Twitter - [@anledruis](https://www.twitter.com/anledruis)

## Acknowledgments

° Chamu => Give me a tip to how to improve my future projects.
- Discord - [@chamu_k_m]

° Darkstar => Helped me improve my project, outling areas that have desnecessary widths and teatching me how to align some objects.
- Discord - [@itsdarkstar]
