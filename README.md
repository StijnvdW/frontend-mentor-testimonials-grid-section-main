# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

#### Desktop

![Desktop](./screenshots/desktop.png)

#### Mobile

![Mobile](./screenshots/mobile.png)


### Links

- Solution URL: [GitHub](https://github.com/StijnvdW/frontend-mentor-testimonials-grid-section-main)
- Live Site URL: [GitHub Pages](https://stijnvdw.github.io/frontend-mentor-testimonials-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

#### Grid area
Each testimonial belongs to a grid area

```css
.testimonial-five {
    grid-area: testimonialFive;
}
```

Depending on the screen size a grid template areas property is defined:

```css
main {
        display: grid;
        grid-template-areas:
        'testimonialOne testimonialOne testimonialTwo testimonialFive'
        'testimonialThree testimonialFour testimonialFour testimonialFive';
        grid-template-rows: repeat(2, 1fr);
        grid-template-columns: repeat(4, 1fr);
    }

```

### Continued development

Not quiet perfect yet:
- Image borders
- Box shadows: no clear specs

## Author

- Frontend Mentor - [@StijnvdW](https://www.frontendmentor.io/profile/StijnvdW)
- GitHub - [@StijndvdW](https://github.com/StijnvdW)
- Twitter - [@StijnvdW86](https://www.twitter.com/StijnvdW86)

