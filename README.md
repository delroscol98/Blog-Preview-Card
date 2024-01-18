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

Challenge #2 from Frontend Mentor. Another small project for me to practice my HTML and CSS skills.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%202024-01-18%20at%209.41.50%E2%80%AFpm.png)

### Links

- Solution URL: [Github](https://github.com/delroscol98/Blog-Preview-Card)
- Live Site URL: [Github Pages](https://delroscol98.github.io/Blog-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

This time I took a Mobile-first workflow approach and styled each HTML element before the next one. Although this took a bit more time, I didn't make as many mistakes as before.

Below are some code snippets I am proud of:

```html
<main class="container">
  <section class="container_display"></section>
  <h3 class="container_learning">Learning</h3>
  <p class="container_date">Published 21 Dec 2023</p>
  <h1 class="container_heading">HTML & CSS foundations</h1>
  <p class="container_para">
    These languages are the backbone of every website, defining structure,
    content, and presentation
  </p>
  <article class="container_author">
    <img
      class="container_author-img"
      src="./assets/images/image-avatar.webp"
      alt="author image"
    />
    <p class="container_author-name">Greg Hooper</p>
  </article>
</main>
```

With the use of Semantic HTML5 and easy-to-read classes, other developers are able to read my code easily.

```css
@media screen and (min-width: 320px) and (max-width: 425px) {
  .container {
    height: 40rem;
    width: 75vw;
  }
}
```

Starting with media queries allowed me to work with the mobile-first approach

### Continued development

For future reference I would like to continue working on mobile-first development and semantic HTML. It's important for me to master the workflow to reduce the amount of bugs in my CSS that makes my websites unresponsive. Additionally, I'd like to continue working on pseudo classes that allow me to interact with different elements.

### Useful resources

- [Mobile-First Design](https://www.youtube.com/shorts/K7vT9DAnqdE) - This helped me gain a basic grasp of Mobile-First Design

## Author

- Website - Collin Del Rosario
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/delroscol98)
