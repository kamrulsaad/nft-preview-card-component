# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202022-03-13%20191127.png)


### Links

- Solution URL: (https://github.com/kamrulsaad/nft-preview-card-component)
- Live Site URL: (https://kamrulsaad.github.io/nft-preview-card-component/index.html))

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I have learnt how I can overlay the show icon over and image by using custom CSS only. Check out the code below to get it.

```css
.image-box{
    position: relative;
}

.image-box:hover .overlay {
    opacity: 1;
}

.icon{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    -ms-transform: translate(-50%,-50%);
    -webkit-transform: translate(-50%,-50%);
}

.overlay{
    position: absolute;
    border-radius: 10px;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    width: 100%;
    height: calc(100% - 3px);
    transition: .5s ease;
    opacity: 0;
    background-color: hsla(178, 100%, 50%,0.4);
}

.image{
    opacity: 1;
    transition: .5s ease;
    max-width: 100%;
    border-radius: 10px;
}
```


### Useful resources

- [Example resource 2](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This is an amazing article which helped me finally understand how to show overlay on hovering over images. I'd recommend it to anyone still learning this concept.


## Author

- GitHub - [Kamrul Saad](https://github.com/kamrulsaad)
- Frontend Mentor - [@kamrulsaad](https://www.frontendmentor.io/profile/kamrulsaad)
- LinkedIn - [@yourusername](https://www.frontendmentor.io/profile/yourusername)




