# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor] (https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot.png](Screenshot.png)

### Links

- Solution URL: [https://github.com/hardaway-2000/Social-Links-Profile.git](https://github.com/hardaway-2000/Social-Links-Profile.git)
- Live Site URL: [https://hardaway-2000.github.io/Social-Links-Profile/](https://hardaway-2000.github.io/Social-Links-Profile/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Flexbox
- Desktop-first workflow

### What I learned

One of the main challenges I overcame in this project was handling complex hover states. I needed the text inside a link (`<a>`) to change color when the user hovered over the parent container (`<div>`), not just the link itself.

I solved this by using the specific CSS selector `.class:hover a`.

```css
/* When the user hovers over the button container */
.social-links:hover {
  background-color: hsl(75, 94%, 57%);
  color: hsl(0, 0%, 8%);
  cursor: pointer;
}

/* Force the link text inside to change color too */
.social-links:hover a {
  color: hsl(0, 0%, 8%);
}
```

## Author

- Name - Mohamed Alaa
- Frontend Mentor - [@hardaway-2000](https://www.frontendmentor.io/profile/hardaway-2000)
