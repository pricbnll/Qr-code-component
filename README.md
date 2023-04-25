# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

[Screenshoot my solution for the Qr code component](./images/qr-code.png)


## My process

Try to do all by my self with confidence after 6 month a part of all technology and studies, so I needed to see some videos about flexbox and understand about 'min-height' and 'min-width'.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned


```css
 body{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
 }

.container{
    max-width: 300px; /*tamanho do container/"o que é branco"*/
    /* display: block; */
    margin: 0 1rem; /* nao se aproximar da margin lateral quando mobile */
    background-color:  hsl(0, 0%, 100%); 
    border-radius: 15px;
    padding: 15px; /* serve para o qr code img e o texto nao ficarem encostados direto na bosrda do container (branco) */
    text-align: center; 
}
```

### Continued development

I want to continue focusing on in future projects how to provide clean code.  I donn´t understand why so many div inside div yet. How can I use flexbox and grid and the responsive mode.


### Useful resources

- [Centralizar no CSS](https://www.youtube.com/watch?v=Cu-HP-gvggg) - flexbox

## Author

- Frontend Mentor - [@Pricbnll](https://www.frontendmentor.io/profile/Pricbnll)

## Acknowledgments

Try and keeping trying. Ask for help and watch videos a lot.
