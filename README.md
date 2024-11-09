# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-   See hover and focus states for all interactive elements on the page

### Screenshot

![](./image.png)

### Links

-   Solution URL: [Add solution URL here](https://your-solution-url.com)
-   Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   Mobile-first workflow

### What I learned

Mainly did this apart of the learning path for frontend mentor. `box-sizing` attribute is important.

```html
<img
    class="avatar--image"
    src="./assets/images/avatar-jessica.jpeg"
    alt="avatar image" />
<h1>Jessica Randall</h1>
<address class="address">London, United Kingdom</address>
<p class="summary">"Front-end developer and avid reader."</p>
```

```css
.links {
    background-color: var(--grey-700);
    padding: 0.5rem;
    width: 100%;
    display: block;
    text-decoration: none;
    color: var(--white);
    border-radius: 0.3rem;
    box-sizing: border-box;
    cursor: pointer;
    transition: cubic-bezier(0.165, 0.84, 0.44, 1) 0.25s;
    font-weight: 600;
    font-size: 12px;
}
```

## Author

-   Website - [Dylan Heslop](https://linkedin.com/heslopd23)
-   Frontend Mentor - [@dylan-dot-c](https://www.frontendmentor.io/profile/dylan-dot-c)