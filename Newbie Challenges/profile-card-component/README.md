# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
Profile Card Component Solution 

### The challenge

- Build out the project to the designs provided

### Screenshot


### Links

- Solution URL: [GitHub Repo](https://github.com/KaushalSonic/Frontend-Mentor/tree/main/Newbie%20Challenges/qr-code-component-main)
- Live Site URL: [Visit](https://qr-code-component-sable-eight.vercel.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- ::before and ::after Pseudo selectors

### What I learned

I learnt and use ::before and ::after pseudo selector for placing two images in the background.


```html
<div class="wrapper" role="document"></div>
```
```css
.wrapper{
    position: relative;
    width: 100%;
    height: 100dvh;
    display: grid;
    place-items: center;
    background-color: var(--primary);
    overflow: hidden;
    z-index: -1;
}
.wrapper::before{
    content: url('./images/bg-pattern-top.svg');
    position: absolute;
    top: -33rem;
    left: -18.2rem;
    z-index: -1;
}
.wrapper::after{
    content: url('./images/bg-pattern-bottom.svg');
    position: absolute;
    bottom: -40.5rem;
    right: -14.2rem;
    z-index: -1;
}
```


### Continued development

I am working forward to take another challenge from Frontend Mentor.


## Author

- Website - [Kaushal Kishore](https://my-portfolio-one-one.vercel.app/)
- Frontend Mentor - [@KaushalSonic](https://www.frontendmentor.io/profile/KaushalSonic)
- Linkedin - [Kaushal Kishore](https://www.linkedin.com/in/kaushal-kishore-b373111a8/)
