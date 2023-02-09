# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H), which I built. Frontend Mentor challenges help to improve coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.jpg)
![QR Code Component sample image](https://laurenc2022.github.io/qr-code-component/design/desktop-preview.jpg)

### Links

- Solution URL: [Solution URL here](https://github.com/LaurenC2022/qr-code-component.git)
- Live Site URL: [Live site URL here](https://laurenc2022.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The QR Code Component exercise showcases my HTML and CSS skills. I use flexbox to center the QR Code Component and CSS grid to fix the size of the component for all screen sizes. The Figma design file is almost identical for mobile and desktop browser sizes. The difference is the amount of blue background color outside of the component. For this reason no media query is used at this time. Instead, the width of the outside background section is responsive. See code snippet below showing the width set to adjust for any screen size. No media query is included or needed. 

```css
.qr-code-component-section {

    width: 100%; 
    height: 667px; 
    background-color: var(--qr-code-component-section-color);

    /*layout: set qr-code-component-section as flex container  */
    display: flex;
    justify-content: center;
    align-items: center;
}
```

### Continued development

I did run into HTTP and Javascript errors when checking the layout against Chrome and Firefox browser developer tools. The issues regard cookies and HTTP requests. The issue is outside of the scope for this exercies and is above my skill level at this time. I will come back to this at a later date and after I learn HTTP. MDN Web Docs has a detailed guide on HTTP.  

## Author

- Website - [Lauren Collins](https://laurencollins.dev)
- GitHub - [@LaurenC2022](https://github.com/LaurenC2022)
- Frontend Mentor - [@LaurenC2022](https://www.frontendmentor.io/profile/LaurenC2022)
- Twitter - [@Home_At_Heart_](https://twitter.com/Home_At_Heart_)

## Acknowledgments

Thank you Matt Studdert and the staff at Front End Mentors. Your work is allowing me to gain confidence, and develop a professional workflow. The work you do is changing my life. I am a stay at home mom working at night to build a career as a software developer. It means so much to me. Within this year, I will be living my dream: I will be a skilled software developer. Your website, and other free and low cost, high quality educational resources are enabling me to achieve my goals. Thank you for your work. 
