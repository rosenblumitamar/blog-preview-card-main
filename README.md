# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

#### Desktop Preview
![desktop-design-solution](/design/desktop-design-solution.png)

#### Mobile Preview
![mobile-design-solutio](/design/mobile-design-solution.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS Variables
- CSS Flexbox

### What I learned

I learned how to implement CSS Variables in a project and how to make responsive font-size using css clamp() function.

```css
:root {
  --white: #ffffff;
  --yellow: #f4d04e;
  --grey: #6b6b6b;
  --dark: #121212;
}
```

```css
body {
  font-family: "Figtree", sans-serif;
  font-size: clamp(15px, 3.7vw, 16px);
  color: var(--dark);
  background-color: var(--yellow);
}
```

### Continued development

I'm to continue honing my skills in responsive web design, focusing specifically on mastering CSS Flexbox and Grid techniques.

### Useful resources

- [MDN - CSS clamp() function](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) - This helped me to understand the CSS clamp() function.
- [W3Schools - CSS clamp() function](https://www.w3schools.com/cssref/func_clamp.php) - This helped me to understand the CSS clamp() function.

## Author

- Frontend Mentor - [@rosenblumitamar](https://www.frontendmentor.io/profile/rosenblumitamar)
- Twitter - [@rosenblumitamar](https://x.com/ItamarRosenblum)#
