# Boolean Academy - Spotify Web (HTML and CSS)

This is a solution to the Exercise 12 of Boolean Academy. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
 

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Desktop](./screens/layouts/spotify-lg.png)
![Mobile](./screens/layouts/spotify-xs.png)

### Links

- Solution URL: [https://github.com/filecc/html-css-spotifyweb](https://github.com/filecc/html-css-spotifyweb)
- Live Site URL: [https://filecc.github.io/html-css-spotifyweb/]([https://your-live-site-url.com](https://filecc.github.io/html-css-spotifyweb/))

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned
To achive the over effect on the image:

```html
<div class="relative hover-img">
    <img src="./img/metal_lifting.jpg" alt="metal">
</div>
```
```css
.hover-img:hover::after {
    content: '\f144';
    font-family: 'Font Awesome 5 Free';
    font-weight: 900;
    position: absolute;
    width: 100%;
    height: 100%;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 4rem;
    color: white;
    background-color: #0008;
}
```
