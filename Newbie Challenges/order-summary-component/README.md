# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

Order Summary Card Solution

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot
<img width="400" alt="blog1" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/94548c50-c143-4047-bf6b-130ef817f70b">

### Links

- Solution URL: [GitHub Repo](https://github.com/KaushalSonic/Frontend-Mentor/tree/main/Newbie%20Challenges/order-summary-component)
- Live Site URL: [Go](https://order-summary-component-sigma-ten.vercel.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I learnt how to mimic the background by using background image and background color.

See below:

```html
<div class="wrapper" role="document">
```
```css
.wrapper{
    width: 100%;
    height: 100dvh;
    display: grid;
    place-items: center;
    background-color: var(--Pale-blue);
    background-image: url('./images/pattern-background-desktop.svg');
    background-repeat: no-repeat;
    background-position-y: -5.5rem;
}
```
For Mobile Responsiveness

```css
@media screen and (max-width: 400px){
    html{
        font-size: 13.5px;
    }
    .wrapper{
        background-image: url('./images/pattern-background-mobile.svg');
        background-size: 115%;
        background-position: top;
    }
}
```

### Continued development

Next time I make sure to build layouts using 90% of the browser scale.


## Author

- Website - [My Portfolio](https://my-portfolio-one-one.vercel.app/)
- Frontend Mentor - [@KaushalSonic](https://www.frontendmentor.io/profile/KaushalSonic)
- Linkedin - [Kaushal Kishore](https://www.linkedin.com/in/kaushal-kishore-b373111a8/)

