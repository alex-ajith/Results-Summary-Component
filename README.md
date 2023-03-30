# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: (https://github.com/alex-ajith/Results-Summary-Component.git)
- Live Site URL:  (https://alex-ajith.github.io/Results-Summary-Component/)

## My process

### Built with
- Semantic HTML5 markup
- Flexbox
- Mobile first and Responsive CSS

### What I learned

Learned concept of CSS Flexbox and it's properties. Learned how to use media queries to make the webpage responsive.

```html
  <div class="container">
    <div class="results-card"></div>
    <div class="sumary-card"></div>
  </div>

```
```css
@media screen and (max-width: 650px){
    .container {
        flex-direction: column;
        margin: 0 16px;
    }
    .results-card {
        width: inherit;
        box-shadow: none;
    }
    .summary-card {
        width: inherit;
    }
}
```
### Continued development

Further planning to enhance in Responsive Design, CSS Grid and Flexbox.

## Author

- Frontend Mentor - [AJITH M](https://www.frontendmentor.io/profile/alex-ajith)
- LinkedIn - [AJITH M](https://www.linkedin.com/in/ajith-m-709b29233/)

## Acknowledgments

I've referred some, gained knowledge from the videos of youtuber @MrCoderYt, @TheCoderCode and others.
