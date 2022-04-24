# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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
  - [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [github](https://github.com/L1m1tz/nft-preview-card-component)
- Live Site URL: [Gitpages](https://l1m1tz.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- asymmetric division model
- CSS custom properties
- Flexbox
- CSS Grid
- Web-first workflow

### What I learned

In this challange i improved my understanding on grid and flexbox, i also learned how to put an overlay on an image.
To see how you can add code snippets, see below:

```html
    <div class="card-img">
      <div>
        <img
          id="img"
          src="images/image-equilibrium.jpg"
          alt="Equilibrium image"/>
        </div>  
        <div class="icon">
           <img src="images/icon-view.svg" alt="icon" />
          </div>
        </div>
```
```css
#img {
    position: absolute;
    background-color: hsl(178, 100%, 50%);
    border-radius: 10px;
    width: 300px;
    transition: 0.5s ease;
    backface-visibility: hidden;

}

.icon {
    background-color: hsl(178, 100%, 50%);
    transition: 0.5s ease;
    height: 290px;
    width: 290px;
    border: 5px solid hsl(178, 100%, 50%);
    border-radius: 13px;
    opacity: 0;
    position: relative;
    top: 30%;
    left: 50%;
    transform: translate(-50%, 0%);

}

.icon>img {
    margin: 120px auto;
    display: block;
    opacity: 1;
    background-blend-mode: multiply;

}
```


### Continued development

In this challenge I really struggled on the layout of the overlay since the image would overflow over the card and elements would go out of alignment. 
I will continue to improve my understanding of relative and absolute positioning and I will also work on improving my understanding of flexbox and grid.

### Useful resources

- [Revisiting flexbox using a complete guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me remember how to align elements in a flex display.
- [overlay hover effects](https://codepen.io/nxworld/pen/ZYNOBZ) - This was a great reference on how to use positioning and css opacity.
- [image overlay effects](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - another look at how overlays works
- [motivation](https://merhanmostafa47.github.io/NFT-preview-card-component/) - i used this as motivation for the overlay on hover effect


## Author

- Website - [Andrewmk](https://www.siteforge.co.za)
- Frontend Mentor - [@L1m1tz](https://www.frontendmentor.io/profile/L1m1tz)
- linkIn - [@Andrew Mokhabukhi](https://www.linkedin.com/in/andrew-mokhabukhi-990a3420a/)


## Acknowledgments

I'd like to thank github user merhanmostafa47 for completing his project, because at some point i though the hover was impossible.
