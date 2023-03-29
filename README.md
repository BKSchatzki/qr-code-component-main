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

This project was a simple warmup to "dust out the cobwebs" after a break from learning. It is a simple QR code component done by eye to an example .jpg file.

### Screenshot

![](.images/screenshot.png)


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/qr-code-component-vanilla-flexbox-vnd_IHPdxO)
- Live Site URL: [Live Site](https://bkschatzki.github.io/qr-code-component-main/)

## My process

First, some housekeeping. The downloadable package didn't contain an external stylesheet, nor did it include links to the font needed in the design document. Next, the image needed to be added and sized. I eyeballed this since I do not have access to the design files. I had to play with the padding and border radius to get it to look right. The same had to be done for the font, which needed to be wrapped in tags first. I went back and changed the root rem size to 10px, then started to push the font sizes around. Finally, I added the colors, centered the card, then brought the footer up into the container element. I had to go back and make the document more accessible, and I had a couple of redundant styling to remove.

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

A lot of styling I do is redundant, and I still struggle slightly with keeping track of parent and container elements. I have a habit of just wrapping something inside of a div to style it together, and can end up with too many layers. As simple as this was, I still applied some unecessary styling to a container initially. I also worked a little with inherited properties, and refreshed my memory of how that works and how to keep code relatively dry.

### Continued development

Hopefully, I'll be able to integrate something like this with a QR code generator in the future. I also want to be able to drop this component into other pages.

## Author

- Website - [Brendan K. Schatzki](https://github.com/BKSchatzki)
- Frontend Mentor - [@BKSchatzki](https://www.frontendmentor.io/profile/BKSchatzki)
- Twitter - [@BKSchatzki](https://www.twitter.com/bkschatzki)

## Acknowledgments

Thank you to [@Hassiai](https://www.frontendmentor.io/profile/Hassiai) for giving me feedback on my initial solution. I was able to implement their suggestions very clearly.