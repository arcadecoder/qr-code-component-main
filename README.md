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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
A QR component frontend web view. 

### Screenshot

![<img src="./images/solution-screenshot.PNG">](./images/solution-screenshot.PNG)

### Links

- Solution URL: [solution](https://github.com/arcadecoder/qr-code-component-main)
- Live Site URL: [Deployed on Vercel](https://qr-code-component-main-gamma-seven.vercel.app/)

## My process

### Built with

- HTML5 
- CSS custom properties




### What I learned

I refreshed my memory on how to center  components in css, by first creating a container and then justifying the content in the middle. 


```html
<div class="centre">
  <div class="card">
    <img src="./images/image-qr-code.png" />
    <div class="text-content">
      <h2> Improve your front-end skills by building projects </h2>
      <p> Scan the QR code to visit Frontend Mentor and take your coding skills to the next level </p>
      <div class="attribution">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
        Coded by <a href="#"> Arcade coder </a>.
      </div>
    </div>
    
    
  </div>
   </div>
```
```css
.centre {
    display: flex;
    align-items: center;
    justify-content: center;
}

```
