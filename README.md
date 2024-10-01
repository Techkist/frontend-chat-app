# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Links

- Live Site URL: (https://techkist.github.io/mobile-responsive-frontend-chat-app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

I learned a lot in this project, especially creating a custom radio button. i couldnt find the animate chat interface "**Bonus**: See the chat interface animate on the initial load" maybe that was for those using the figma file.

To see how you can add code snippets, see below:

```css
span {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;

  width: 1.5rem;
  height: 1.5rem;
  border: 1px solid var(--color-very-light-magenta);
  border-radius: 50%;

  &::before {
    display: block;
    position: absolute;
    content: "";
    width: 75%;
    height: 75%;
    background-color: var(--color-light-Violet);
    border-radius: 50%;

    opacity: 0;
  }
}
```

### Continued development

I would like to do projects with grid layouts so as to enable me understand th econcept of grid layouts better.

### Useful resources

Actually i had to use google to research on some things i found challenging,
www.w3schools.com helped me a lot

## Author

- Frontend Mentor - [@Techkist](https://www.frontendmentor.io/profile/Techkist)
- Twitter - [@techkist](https://www.twitter.com/yourusername)

## Acknowledgments

I acknowledge jonas schmedmann of udemy, his Trillo and Natours projects helped me a lot in terms of referencing and code organizing. Thank you so much Jonas ☺️, i wish u could see this smiles.
