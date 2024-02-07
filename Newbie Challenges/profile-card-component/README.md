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


## Overview
Profile Card Component Solution 

### The challenge

- Build out the project to the designs provided

### Screenshot
<img width="400" alt="profile-card" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/655a147c-32ac-4b89-8327-af2780655a48">

### Links

- Solution URL: [GitHub Repo](https://github.com/KaushalSonic/Frontend-Mentor/tree/main/Newbie%20Challenges/profile-card-component)
- Live Site URL: [Visit](https://glistening-melomakarona-d341bc.netlify.app/)

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
    /* Using vw, vh (viewport units) for resolve issue of displacement of images while upscale or downscale browser. */
    bottom: 35vh;
    right: 51.8vw;
    z-index: -1;
}
.wrapper::after{
    content: url('./images/bg-pattern-bottom.svg');
    position: absolute;
    top: 51.5vh;
    left: 47.5vw;
    z-index: -1;
}
```


### Continued development

I am working forward to take another challenge from Frontend Mentor.


## Author

- Website - [Kaushal Kishore](https://my-portfolio-one-one.vercel.app/)
- Frontend Mentor - [@KaushalSonic](https://www.frontendmentor.io/profile/KaushalSonic)
- Linkedin - [Kaushal Kishore](https://www.linkedin.com/in/kaushal-kishore-b373111a8/)
