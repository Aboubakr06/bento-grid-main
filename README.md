# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

-Mobile version-

![photo](./design/mobile-design.jpg)

 -Desktop version

![photo](./design/desktop-design.jpg)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/bento-grid-O07DTWczED)
- Live Site URL: [Live Site](https://musical-toffee-739d66.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
 article {
        display: grid;
        gap: 1rem;
        grid-template-columns: repeat(4, 1fr);
        grid-template-rows:  1fr;
        grid-template-areas: 
            'a b b c'
            'a e f c'
            'd e f c'
            'd g h h'
                    ;
    }
    
    .section1 {
        grid-area: b;
        font-size: 1.5rem;
    }
```

### Continued development

The area i want to focuse on more is CSS Grid.

### Useful resources

- [W3School](https://www.w3schools.com/cssref/pr_grid.php) - This helped me understanding and using CSS Grid on my project.

## Author

- Frontend Mentor - [@Aboubakr06](https://www.frontendmentor.io/profile/Aboubakr06)

