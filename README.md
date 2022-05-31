# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

This page was created with Mobile-First in mind. Therefore, viewers can

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page (except those in the very last sentence in the footer)

However, the page might not be optimized for all screen sizes. 

> More optimization to be added in the future.

### Screenshot

![](images/Huddle%20landing%20page%20Screenshot.png)

### Links

- ~~Solution URL: [Solution URL here](https://solution-url.com)~~
- ~~Live Site URL: [Live site URL here](https://live-site-url.com)~~

> Links to be added 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

There had been difficulties trying to change the size of the illustration image. Because of it being larger than the container, the image overflows and white spaces appear horizontally and vertically. 

The following method didn't work :

```css
  .illustration {
    transform: scale (x,y);
  }
```
The solution to it:
```css
  .illustration {
    width: 100%;
  }
```
The above properties set the illustration to be at 100% length the same as that of its container. If the container gets smaller in size, the illustration gets smaller too, and in a proportional manner.

When creating layouts, the mobile design was simple.
In the desktop design, CSS Grids was used.
- Firstly, 2 columns and 2 rows are added for the grid. The header (containing the logo and the illustration) was set to take grid row line 1 to 3, meaning it covers the first whole column. 
- Secondly, align properties were used to tweak the positioning.

### Continued development

Since the project contains only basic HTML and CSS, there are a lot of concepts and techniques to implement in the future. 

- Bootstrap/Foundation/...other CSS Frameworks

- JavaScript

### Useful resources

- [w3schools](https://www.w3schools.com/) - This helped me for checking up HTML and CSS properties.
- [Traversy Media](https://www.youtube.com/watch?v=0xMQfnTU6oo&t=889s) - This is an amazing video on CSS Grids by Brad Traversy. He's one of the amazing developers out there on the platform.

## Author

- Frontend Mentor - [@saikham1510](https://www.frontendmentor.io/profile/saikham1510)
- ~~Website - [Name here](https://www.site.com)~~
- ~~Twitter - [@username](https://www.twitter.com/username)~~