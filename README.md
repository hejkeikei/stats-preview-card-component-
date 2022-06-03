# Frontend Mentor - Stats preview card component

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

This challenge is to build out this card component and get it looking as close to the design as possible.

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- Desktop
  ![screenshot](./screenshot_desktop.jpg)
- Mobile
  ![screenshot](./screenshot_mobile.jpg)

### Links

- Solution URL: https://hejkeikei.github.io/stats-preview-card-component-main/

## My process

- Write with semantic markup.
- Set all root figures and font.
- Plan the layout.
- Go through validators.
- Write CSS for general tags.
- Write classes' and ids' style.
- Responsive design
- Get all CSS done, check on both desktop and mobile.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Overlay color on background image

```css
.imgBox {
  background-image: linear-gradient(
      to bottom,
      hsla(277, 64%, 61%, 0.3),
      hsla(277, 64%, 61%, 0.3)
    ), url(./images/image-header-desktop.jpg);
  width: 100%;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
.overlay {
  width: 100%;
  height: 100%;
  background-color: var(--violet);
  opacity: 0.8;
  mix-blend-mode: multiply;
}
```

- Mark elements

```html
<p class="fig"><mark>10k+</mark> companies</p>
```

### Continued development

- CTA buttons
- Special effect on displaying figures

### Useful resources

- [CSS mix blend modes](https://css-tricks.com/basics-css-blend-modes/).

## Author

- Codepen - [TingHueiChen](https://codepen.io/TingHueiChen)
- Frontend Mentor - [@hejkeikei](https://www.frontendmentor.io/profile/hejkeikei)
- Twitter - [@hej_keikei](https://twitter.com/hej_keikei)
