# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

* Desktop View <br><br>
  <img width="500" alt="four feature card desktop view" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/b3ec05b3-8f06-4f31-84db-1b5147d3cf40">

* Mobile View <br><br>
  <img width="200" alt="four feature card mobile view" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/a6044ab4-ec9f-4cbc-a9ec-eb5fad588263">
  

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/four-card-feature-section-TtzPQT7BN7)

- Live Site URL: [Visit](https://four-feature-card-kaushalsonic.netlify.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

In this challenge I learnt how to implement given card layouts and alignments using absolute positioning and relative positioning to card and its children.



```html
<div class="card-section">
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
</div>
```
```css
.card{
    position: relative;
    width: 18rem;
    height: 11.5rem;
    background-color: white;
}
.card:nth-child(1){
    position: absolute;
    left: -20rem;
}
.card:nth-child(4){
    position: absolute;
    right: -20rem;
}
```


### Continued development

I will continue this learning path of making hand on learning to implement web desings.


## Author

- Website - [Kaushal Kishore](https://my-portfolio-one-one.vercel.app/)
- Frontend Mentor - [@KaushalSonic](https://www.frontendmentor.io/profile/KaushalSonic)
- Linkedin - [Kaushal Kishore](https://www.linkedin.com/in/kaushal-kishore-b373111a8/)

