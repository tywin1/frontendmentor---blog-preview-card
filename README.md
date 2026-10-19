# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Define the necessary elements and class names in the HTML.
CSS - enter class names and move the elements into correct position.
CSS - add root elements for fonts and colours.
CSS - set colours, alignment, padding, margins, hover/focus colours.

### Built with

- VS Code
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

CSS is still an issue in terms of what selectors and where - these basic challenges are great for reinforcing the stuff I tend to forget.  So what I learned -

- H1 etc elements in a flexbox stretch the full width, so that needs to be overridden for the "Learning" text to avoid the background colour stretching -> align-items: flex-start.
- Similar to above, set specific margin and padding on <h1> and <p> elements to remove their default behaviour.
- If you define left and top borders, right and bottom arent visible by default.  So border-right: none etc is unnecessary.

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- Copilot in Ask mode for some padding/alignment issues, and to remove unnecessary CSS that I'd used.

## Author

- Website - [Tywin1](https://www.github.com/tywin1)