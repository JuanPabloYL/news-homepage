# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects.
ote: Delete this note and update the table of contents based on what sections you keep.\*\*

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was an interesting project, I learned how to toggle the main menu conent without any line of JavaScript code, It helped me to understand better the power of selectors and the functionality that some tags have from it context.

```css
.navigation__toggle:checked ~ .navigation__toggle-label img {
  opacity: 0;
  content: url("../assets/images/icon-menu-close.svg");
  animation: op 500ms ease-in-out forwards;
}
```
