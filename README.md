# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [https://github.com/Elsayed-Ramadan100/Front-End-mentor-Recipe-Page](https://github.com/Elsayed-Ramadan100/Front-End-mentor-Recipe-Page)
- Live Site URL: [https://elsayed-ramadan100.github.io/Front-End-mentor-Recipe-Page/](https://elsayed-ramadan100.github.io/Front-End-mentor-Recipe-Page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Google Fonts](https://fonts.google.com/) - Outfit & Young Serif

### What I learned

In this project, I focused on writing clean, semantic HTML and using CSS for precise styling. I learned how to customize list markers to match a specific design using the `::marker` pseudo-element, which was very useful for the preparation time section:

```css
.time ul li::marker {
    color: hsl(332, 51%, 32%);
    font-weight: 500;
    font-size: 50%;
}

```

I also practiced styling tables efficiently. Instead of adding classes to every row, I used the `:not` pseudo-class to apply borders to all rows except the last one, keeping the HTML clean:

```css
tr:not(.last) {
    border-bottom: 1px solid hsl(30, 18%, 87%);
}

```

### Continued development

In the future, I want to deepen my knowledge of frontend development by taking on more difficult challenges. My next specific goal is to learn and implement **CSS Grid** in complex layouts to expand my styling toolkit beyond Flexbox.

## Author

* Name - Elsayed Ramadan
* GitHub - [@Elsayed-Ramadan100](https://github.com/Elsayed-Ramadan100)
* LinkedIn - [Elsayed Ramadan](https://www.linkedin.com/in/elsayed-ramadan-407626261/)
