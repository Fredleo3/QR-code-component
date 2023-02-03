# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### Screenshot

![Screenshot](https://github.com/Fredleo3/QR-code-component/blob/main/assets/images/Screenshot.PNG)


### Links

- Live Site URL: [QR code component solution](https://fredleo3.github.io/QR-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex


### What I learned

Fit an image inside a container:

```css
.qr-image{    
    object-fit: cover;    
}
```
Distribute the space of the elements according to their importance using flex-grow. In this case, .container contains the main information that should capture the most attention of the user, while .attribution contains informative text that is relegated to the background.

```css
.container{     
    flex-grow: 1;   
}

.attribution { 
    flex-grow: 0;       
}
```

### Continued development

- Flex
- Flex-box
- Flex-grid

### Useful resources

- [Flexbox playground](https://codepen.io/enxaneta/full/adLPwv) - This helped me understand a bit more about how to use the flex container and flex item properties. This page is a great reference about flex properties.


## Author

- GitHub - [Fredleo3](https://github.com/Fredleo3)
- Frontend Mentor - [@Fredleo3](https://www.frontendmentor.io/profile/Fredleo3)



