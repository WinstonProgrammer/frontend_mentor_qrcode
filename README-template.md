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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Screenshot 2025-03-21 at 13-58-34 Frontend Mentor QR code component](https://github.com/user-attachments/assets/13115cdc-d6ec-4d9f-aad5-6955469d276f)

### Links

- Solution URL: [https://your-solution-url.com](https://github.com/WinstonProgrammer/frontend_mentor_qrcode.git)
- Live Site URL:[https://your-live-site-url.com](https://winstonprogrammer.github.io/frontend_mentor_qrcode/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Font style Outfit](https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap)

### What I learned

Firstly, I learned that if I want to use an imported font style (or any kind of style for that matter), I can import it through with the next code:
```html
<style>
  @import url("https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap");
</style>
```

Another thing I learned is that I have to put the link of the sources of images in an abbreviated manner so Github Pages can receive it without much trouble:
```html
<img id="qr-card-img" src="./images/image-qr-code.png" alt="qr code" />
```

Something that complicated me in the development was the struggle to find a way to center the container in the page, but I figured how to do so: First, modify the display manner of the container to a block-like one, then put its left and right margins as auto and, lastly, add some percentage value to the top margin or the bottom margin, depending on the case:
```css
.qr-card {
  background-color: hsl(0, 0%, 100%);
  width: min-content;
  border-radius: 15px;
  align-content: center;
  display: block;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  margin-top: 13%;
}
```

### Continued development

I want to focus myself on to speed up my time in coding pages, specially in centering containers or other elements in a page. Also, I want to undestand the different forms of positions there can be in CSS (flex, absolute, sticky, float, etc.).

### Useful resources

- [Resource 1](https://stackoverflow.com/questions/41468951/images-not-displaying-in-github-pages) - This page helped me to figure out how to make an image appear in Github Pages.
- [Resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius) - This article helped me to know how to curve the borders of a container.
- [Resource 3](https://stackoverflow.com/questions/4973988/why-does-css-not-support-negative-padding) - This article helped me to undestand what values can padding take.

## Author

- Website - [WinstonProgrammer](https://github.com/WinstonProgrammer)
- Frontend Mentor - [@WinstonProgrammer](https://www.frontendmentor.io/profile/WinstonProgrammer)

## Acknowledgments

I want to thank the new Frontend Mentor users who made recently the same qr code challenge, their codes helped me to take inspiration and motivation to do my own.
