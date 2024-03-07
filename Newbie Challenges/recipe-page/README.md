# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

Recipe Page Challenge

### Screenshot

* Desktop View <br><br>
  <img width="350" alt="recipe-desktop" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/b6a1a90f-f614-493d-94cc-c76f8c3145e5">!

* Mobile View <br><br>
  <img width="200" alt="recipe-mobile" src="https://github.com/KaushalSonic/Frontend-Mentor/assets/88739514/51ee1c58-73f8-4dbc-a282-fa7febe74deb">

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/recipe-page-zfd_DZ4cOB)

- Live Site URL: [Visit](https://omelette-recipe-page-kaushalsonic.netlify.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Table, tr, td

### What I learned

I learnt how to implement approx. alignments of row and column data inside the Nutrition section using table tag and order & unordered list items.

To see how you can add code snippets, see below:

```html
<table>
      <tr>
        <td>Calories</td>
        <td class="nutrition-value">277kcal</td>
      </tr>
      <tr>
        <td>Carbs</td>
        <td class="nutrition-value">0g</td>
      </tr>
      <tr>
        <td>Protein</td>
        <td class="nutrition-value">20g</td>
      </tr>
      <tr>
        <td>Fat</td>
        <td class="nutrition-value">22g</td>
      </tr>
</table>
```
```css
table{
    margin-top: 1.3rem;
    width: 100%;
}
table,tr,td{
    font-family: "Outfit", sans-serif;
    font-size: 0.9rem;
    border-bottom: 1px solid var(--Light-Grey);
    border-collapse: collapse;
    margin-top: 1rem;
    padding: 0.8rem 1.8rem 0.69rem 1.8rem;
    color: var(--Dark-Raspberry);
}
.nutrition-value{
    color: var(--Nutmeg);
    font-weight: 600;
    padding-right: 3.2rem;
}
table, tr:last-child, td{
    border-bottom: none;
}
```

### Continued development

I will continue this learning path of making hand on learning to implement web desings.

## Author

- Website - [Kaushal Kishore](https://my-portfolio-one-one.vercel.app/)
- Frontend Mentor - [@KaushalSonic](https://www.frontendmentor.io/profile/KaushalSonic)
- Linkedin - [Kaushal Kishore](https://www.linkedin.com/in/kaushal-kishore-b373111a8/)


