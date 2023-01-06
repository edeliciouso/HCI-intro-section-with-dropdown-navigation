# Quiz 2 - Intro section page with interactive dropdown menu solution

This is a solution to the [Intro section page with interactive dropdown menu Quiz 2 challenge]

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![solution](images/Lol.png)


### Links

- Solution URL: (https://github.com/edeliciouso/HCI-intro-section-with-dropdown-navigation)
- Live Site URL: (https://edeliciouso.github.io/HCI-intro-section-with-dropdown-navigation/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Styled Components](https://styled-components.com/) - For styles
- Custom Font - [Epilogue](https://fonts.googleapis.com/css2?family=Epilogue:wght@500;700&display=swap)


### What I learned

I learned how media queries actually work after a long time, and I learned what the span is used for.

```css
@media(min-width:850px){
  nav{
    position: initial;
    max-width: 80vw;
    height: auto;
    background: transparent;
    margin: 0 2rem;
    flex: 3;
    align-items: center;
    transform: translate(0%);
    }
}
```
```html
<a href="#" class="dropdown">
  <span>Features</span>
  <img src="./images/icon-arrow-up.svg" class="arrow-up">
  <img src="./images/icon-arrow-down.svg" class="arrow-down">
</a>
```


### Continued development

I want to get used to using media queries and to learn more on how to maximise CSS to its full potential, as well as continuing on to learn JavaScript as I don't understand how to use it, which is why it isn't finished.


### Useful resources

- [W3Schools](https://www.w3schools.com/) - This is the website that I mainly use to learn any new syntaxes from any programming language that I'm currently learning.
- [GeeksforGeeks](https://www.geeksforgeeks.org/) - This website gives me more explanation on things that I do not understand yet.


## Your Detail 

- FullName - [Edelyne Keisha]
- StudentID - [2602169850]
- BINUS Email - [edelyne.keisha@gmail.com]


## Acknowledgments

I would like to thank there being websites that help me in figuring out how things work, Youtube also for showing me how the code would work in real time, and my friends in L1BC for helping me when I encountered an error.

