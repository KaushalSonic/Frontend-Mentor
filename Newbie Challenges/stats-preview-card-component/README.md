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
<img width="350" alt="stats desktop" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/6e54db46-bfc9-462a-acf6-7012fc3c1c0f">

* Mobile View
<img width="200" alt="stats mobile" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/1f83d142-823c-40ba-b484-c60081026190">


### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/stats-preview-card-component-cd71WcZtZ4)

- Live Site URL: [Visit](https://stats-card-kaushalsonic.netlify.app/)


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
