# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview]
  - [Screenshot]
  - [Built with]
  - [What I learned]
- [Author]
- [Acknowledgments]

## Overview

A good challenge, it tested my skills in effectively using the grid to centralize the components, I also had a challenge when printing the mobile version but through an example of a colleague I got a better reference to adjust the layout thanks

### Screenshot

![](./images/page.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

to center automatically I used the div "maxcontainer" and inside it I put a "div", and imprinted the components inside this "div".

--html--
<div id="maxContainer">
    <div></div>
</div>
--css--
#maxContainer {
    display: grid;
    grid-auto-flow: row;
    justify-content: center;
    align-items: center;
    height: 100%;
}

## Author

https://github.com/danilosilvamg
https://www.frontendmentor.io/profile/danilosilvamg

## Acknowledgments

through the colleague's solution I used it as a reference to adjust some dimension details that I was having difficulties
https://www.frontendmentor.io/profile/paulaabro
