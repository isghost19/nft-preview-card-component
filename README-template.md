# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

[](./Captura1.PNG)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I am learning more about the use of relative and absolute position.

```html
<div class="equilibrium">
      <img class="img-equilibrium" src="/images/image-equilibrium.jpg" alt="equilibrium">
      <div class="capa">
        <img class="logo-ojo" src="/images/icon-view.svg" alt="view">
      </div>
    </div>
```
```css
.equilibrium {
    position: relative;
    width: 100%;
    height: 100%;
    margin-bottom: 15px;
    cursor: pointer;
}
/* probando la posicion del logo sobre la imagen */

.img-equilibrium {
    width: 100%;
    height: 100%;
    transition: all 500ms ease-out;
    border-radius: 15px;
}

.capa {
    position: absolute;
    top: 0;
    width: 100%;
    height: 98%;
    background-color: hsla(215, 51%, 70%, 0.5);
    transition: all 500ms ease-out;
    opacity: 0;
    visibility: hidden;
    border-radius: 15px;
}
```

### Continued development

quiero utilizar mas el uso del DOM aplicado a paginas dinamicas.



## Author

- Frontend Mentor - [@isghost19](https://www.frontendmentor.io/profile/isghost19)

