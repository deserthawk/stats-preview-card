# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-xNn4j4Bzm)
- Live Site URL: [Live Site URL](https://deserthawk.github.io/stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

The overlay process on the photo was challenging. I set the image file as the background so I could use a different image file during the mobile display.

```css
.preview-card-tumb{
    background-image: url('images/image-header-desktop.jpg');
}

@media (max-width:375px) {
    .preview-card-tumb{    
        background-image: url('images/image-header-mobile.jpg');  
    }
}
```


## Author

- Frontend Mentor - [@deserthawk](https://www.frontendmentor.io/profile/deserthawk)

