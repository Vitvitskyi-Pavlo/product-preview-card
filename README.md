# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (`375px` mobile and `1440px` desktop)
- See hover and focus states for interactive elements

### Screenshot

![Product preview card desktop and mobile preview](./images/screenshot.png)

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/your-solution-link)
- Live Site URL: [Live Demo](https://your-live-site-url.netlify.app)

## My process

### Built with

- Semantic HTML5 markup (`<main>`, `<picture>`, `<article>`)
- CSS custom properties (`:root` variables)
- Flexbox (mobile layout and button alignment)
- CSS Grid (desktop two-column layout)
- Mobile-first workflow using relative `rem` units
- [Google Fonts](https://fonts.google.com/) – Fraunces & Montserrat

### What I learned

- **Art direction with `<picture>`:** Used `<picture>` and `<source media="(min-width: 48rem)">` to serve different product images for mobile and desktop viewports without relying on CSS background tricks.
- **Mobile Flexbox to Desktop Grid:** Structured the card as a single-column flex container on mobile and switched to a `1fr 1fr` CSS Grid at `48rem`, using `height: 100%` and `object-fit: cover` so the product photo matches the height of the text column cleanly.
- **Scalable spacing:** Built typography, padding, gaps, and media queries using `rem` units so the layout scales consistently with root font-size preferences.