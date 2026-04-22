# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- See hover and focus states for all interactive elements on the page (like the card title and author name).
- View a responsive card layout that works on different screen sizes.

### Links

- Solution URL: [Add your solution URL here]
- Live Site URL: [Add your live site URL here]

## My process

### Built with

- Semantic HTML5 markup
- CSS Custom Properties (Variables)
- Flexbox for layout alignment
- Responsive design using percentages (%) for fluid scaling

### What I learned

In this project, I focused on mastering **CSS Positioning** and **Layout debugging**. 

One of my major wins was moving away from relying solely on tutorials. I reviewed positioning concepts (Absolute vs Relative) through YouTube and Gemini, and then applied them by manually adjusting values using the **Browser DevTools**. This "trial and error" approach helped me understand how elements flow in the DOM.

Regarding the **Font styling** issue I encountered (specifically matching the design's typography above the card), I learned that proper `@font-face` integration or Google Fonts imports are crucial for achieving pixel-perfect designs.

```css```
/* Example of using percentages for fluid responsiveness */
.card-container {
  width: 90%;
  max-width: 384px;
  margin: 0 auto;
}

/* My focus on hover states */
.card-title:hover {
  color: var(--yellow-primary);
  cursor: pointer;
}

### Continued development
For my next projects, I plan to focus on:

Layout Principles: Deepening my understanding of how to structure complex layouts more efficiently.

Advanced CSS: Moving from basic positioning to mastering CSS Grid and more complex responsive patterns.

### AI Collaboration
I collaborated with Gemini during this project for:

Project Structure: Organizing my files and folders according to best practices.

Documentation: Refining this README file to present my work professionally.

Responsive Strategies: Discussing the benefits of using percentages (%) instead of fixed pixels (px) to ensure the card scales well on various devices.

### Author
Website - Zaki Alkhalaf
Frontend Mentor - @zakialkhaf16