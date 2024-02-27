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

<img width="350" alt="social-links ss" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/4b9160af-8d4f-47d5-a3e1-7d722ea6e7a7">


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
