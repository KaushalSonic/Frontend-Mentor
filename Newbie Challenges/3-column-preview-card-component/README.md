# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
3-Column Preview Card Component Challenge

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

* Desktop View
<img width="350" alt="3card-desktop-view" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/24429566-97ef-4de8-9f86-d9412c55c4af">
<img width="350" alt="active state" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/9db53ac0-8f1b-4abc-aff6-4a49abc65df5">

* Mobile View
<img width="200" alt="mobile view" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/b2cdf5d2-b389-4a0b-b066-0ce691a2e94b">

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/social-links-profile-g2bEW2tIof)

- Live Site URL: [Visit](https://social-links-profile-kaushalsonic.netlify.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid


### What I learned

In this challenge I learnt to use grid layout with different screen sizes like desktop and mobile and make different layout acccording to that.

3 Columns and 1 Row layout on desktop view

```css
main{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: 1fr;
}
```

1 Column and 3 Rows layout on the mobile view @ less than 400px

```css
main{
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: repeat(3, 1fr);
}
```


### Continued development

I keen to develop and continue these challenges as I am learing to implement different layouts and features.


## Author

- Website - [Kaushal Kishore](https://my-portfolio-one-one.vercel.app/)
- Frontend Mentor - [@KaushalSonic](https://www.frontendmentor.io/profile/KaushalSonic)
- Linkedin - [Kaushal Kishore](https://www.linkedin.com/in/kaushal-kishore-b373111a8/)
