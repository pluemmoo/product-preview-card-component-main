## Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
- [Table of contents](#table-of-contents)
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

USers shoud be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

mobile-view:
![](images/mobile-view.png)

desktop-view:

![](images/desktop-view.png)

### Links

- Solution URL: https://github.com/pluemmoo/product-preview-card-component-main.git
- Live Site URL: https://product-preview-card-component-main-inky-nine.vercel.app/


## My Process 

### Built with

- Semantic HTML5 markup
- Syntactically Awesome Styles Sheets
- Flexbox
- Mobile-First workflow

### What I learned

I have learned how to use flexbox to adjust my component. I used media quries to switch image between desktop image and mobile image which make component more reponsible.


centering component:
```css
.wrapper {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```

switching image:
```css
.img-mobile {
    width: 100%;
}

.img-desktop {
    display: none;
}
```
```css
@media screen and (min-width: 1440px) {
    .img-mobile {
        display: none;
    }

    .img-desktop {
        display: block;
        width: 30rem;
    }
}
```



### Continued development

In the next project, i will focus on javascript and CSS Grid.

### Useful resources

- https://stackoverflow.com/questions/27853884/media-queries-and-image-swapping - this helped me when I'm struggling with image switching

## Author

- Website - [Chaiwat Plongkaew](https://pluemmoo.github.io/)
- Frontend Mentor - [@pluemmoo](https://www.frontendmentor.io/profile/pluemmoo)