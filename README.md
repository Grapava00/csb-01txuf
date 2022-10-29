# tip-calculator

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Calculate the correct tip and total cost of the bill per person

### Screenshot
![image](https://user-images.githubusercontent.com/85571784/198854288-eceba62f-5e62-4c96-95cf-0d07567838f3.png)
![image](https://user-images.githubusercontent.com/85571784/198854313-e96bcb24-7f96-425d-b5b5-62675ce84300.png)

### Links

- Solution URL: https://github.com/Grapava00/tip-calculator
- Live Site URL: https://csb-01txuf.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library

## What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
input:focus {
  outline: 2px solid var(--Strong-cyan);
  caret-color: var(--Strong-cyan);
}
}
```

news : 
- caret-color property.

```js
 function handleChange(event) {
    const { value, name, maxLength } = event.target;
    setData((prevData) => ({
      ...prevData,
      [name]: Number.isInteger(value)
        ? parseInt(value.slice(0, maxLength), 10)
        : parseFloat(value.slice(0, maxLength))
    }));
  }
```
News : 
- Number object  
- isInteger function 

## Author

- Frontend Mentor - [Grapava00](https://www.frontendmentor.io/profile/Grapava00)

## Acknowledgments

I would like to express my special thanks to my mentor Beka Zandukeli, who provided me with valuable help.

