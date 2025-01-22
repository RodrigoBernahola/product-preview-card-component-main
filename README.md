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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Alt text](./images/mobileScreenshot.png?raw=true "Mobile version")
![Alt text](./images/desktopScreenshot.png?raw=true "Desktop version")


### Links

- Live Site URL: (https://rodrigobernahola.github.io/product-preview-card-component-main/)

## My process

I started coding the HTML first which was pretty easy , then i proceeded with the styling using flexbox for almost everything in the layout.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learned to use media queries and to style images that fill their container with a good quality.


```
@media (min-width: 1440px) { 

    .first-image {
        display: none;
    }

    main {
        flex-direction: row;
    }

    .second-image {
        display: block;
        width: 350px;
        height: 367px;
        object-fit: cover;
    }

    .second {
        padding: 16px;
    }
    
    h1 {
        margin-bottom: 18px;
    }

    p {
        margin-bottom: 20px;
    }

    .price-container {
        margin-bottom: 16px;
    }

    p.left {
        font-size: 30px;
    }

    p.right {
        font-size: 18px;
    }

}
```


### Continued development

I would like to do a few exercises extra and then starting to learn grid.

### Useful resources

https://developer.mozilla.org/en-US/

https://stackoverflow.com/


## Author

- Frontend Mentor - @RodrigoBernahola
