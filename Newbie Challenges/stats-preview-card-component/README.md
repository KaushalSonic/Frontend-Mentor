# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
Stats Preview Card Component Challenge

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

* Desktop View
<img width="350" alt="3card-desktop-view" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/24429566-97ef-4de8-9f86-d9412c55c4af">

* Mobile View
<img width="200" alt="mobile view" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/b2cdf5d2-b389-4a0b-b066-0ce691a2e94b">

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/3-column-preview-card-component-vUpy0Dp4bT)

- Live Site URL: [Visit](https://main--3card-component-kaushalsonic.netlify.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

In this challenge I leant to implement background-blend-mode custom property to mimic the image design given.


```html
<div class="banner"></div>
```

```css
.banner{
    position: relative;
    background-image: url('./images/image-header-desktop.jpg');
    background-size: cover;
    background-color: var(--Soft-violet);
    background-blend-mode:hard-light;
}
.banner::before{
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: var(--Dark-desaturated-blue);
    opacity: 0.5;
}
```

### Continued development

I will continue takedown more challenges in the future.


## Author

- Website - [Kaushal Kishore](https://my-portfolio-one-one.vercel.app/)
- Frontend Mentor - [@KaushalSonic](https://www.frontendmentor.io/profile/KaushalSonic)
- Linkedin - [Kaushal Kishore](https://www.linkedin.com/in/kaushal-kishore-b373111a8/)
