# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Acknowledgments](#acknowledgments)

## Overview 

### The Challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Huddle Landing Page](images/huddle.jpg)

### Links

- [GitHub Repo URL](https://github.com/adrvnc/huddle-landing-page-1)
- [Live Site URL](https://adrvnc.github.io/huddle-landing-page-1/)

## My Process


### Built With 

- HTML 
- CSS
- Bootstrap 5.1.3
### What I Learned 

I familiarized myself with using the `:hover` selector. I used it to
change the colors for all of the interactive elements on the page.  
### Continued Development 
I want to have a better understanding of the CSS Box Model. 
More specifically, as it relates to implementing `margin` 
and `padding` properties. 

### Useful Resources 

- [CSS :hover Selector](https://www.w3schools.com/cssref/sel_hover.asp) - Used this to change the colors for the register button and the social media links when the user mouses over it. Recommended for developers who want to create hoverable links.  

## Acknowledgements

I want to give a shoutout to Sofiullah Chowdhury's 
[CodePen solution](https://codepen.io/iamsofiullah/pen/zYzxRGQ).
I used the following code snippet.

```
.social a:hover i {
  color: hsl(300, 69%, 71%);
}

.social a i:hover::after {
  border-color: hsl(300, 69%, 71%);
}

``` 
This solution helped me when I got stuck trying to
create hoverable social media links. I modified the code to 
match what I was trying to accomplish with my project. 

