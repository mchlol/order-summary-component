# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![screenshot](./images/screenshot.jpg)

### Links

- Live Site URL: [Live site](https://mchlol.github.io/order-summary-component/)

## My process

Before starting:
- My first step is to take the provided design screenshot into Illustrator, and create a wireframe around it. Doing this first helps me organise the sections in order to tackle them one by one.
- I then go through the style guide and add the provided info into my stylesheet, including importing the font from Google Fonts. (remembering also to link to the stylesheet in the html file).
- Next I go through the html file and start assigning tags (such as h1, p, button, etc) to the provided content. 
- The next step is to starting dividing the content into sections. Usually for a web page I would use section/main/article tags but as this case is quite basic, I will use divs to keep it simple.
- The above step also includes creating classes and giving them simple but descriptive names.
- Once I have all my content organised I'll start working on my stylesheet to match the design.
- Finally I will use flexbox to organise all the content as per the design.
- ...
- Profit!

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

During & after completion:
- Trouble aligning the content div vertically. Initially I used flexbox with `justify-content: center` and `align-items: center` but the content div was still aligned left. I added `margin: auto` which centered the content horizontally and then later after some mucking around also added `margin-top` which...didn't work! Surprise! After looking at the properties in dev tools I got rid of the whole bloody flexbox and set ONE margin property, `margin: 50px auto` 😅
- Trouble using align-self on the 'change' link. I added another container around the other 2 items and used `space-between` to push them away.
- Trouble rounding the corners on the content div, but the hero illustration having square corners. I used `object-fit: cover` and `overflow: hidden` on the image to correct this. 
- Workflow issue - this is probably due to inexperience, but I found myself jumping around a bit. I would be working on one thing, then notice another issue and go to fix that, then notice something else and so on. I need to stay focused on one issue at a time. 


### Continued development

I struggled with flexbox here, so definitely before I tackle another one of these I'm going to take this course - https://flexbox.io/ - and maybe read a book on concentration 😅


### Useful resources

- The Odin Project (https://www.theodinproject.com/) - An incredibly helpful learning resource that I would recommend to anyone learning front end development, it does not hold your hand and makes you work hard on your own without giving you the answers. I've created my own notes from the Knowledge Check at the end of each lesson, and any other notes I wanted to research along the way, that I can refer back to.
- [Flexbox Zombies](https://mastery.games/flexboxzombies/) - This really helped me get used to the various properties and syntax for using Flexbox.

## Author

- Github - (https://github.com/mchlol)
- Frontend Mentor - @mchlol (https://www.frontendmentor.io/profile/mchlol)
