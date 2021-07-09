# Frontend Mentor - Pod request access landing page solution

This is a solution to the [Pod request access landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pod-request-access-landing-page-eyTmdkLSG). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements
- Receive an error message when the form is submitted if:
  - The `Email address` field is empty should show "Oops! Please add your email"
  - The email is not formatted correctly should show "Oops! Please check your email"

### Screenshot

![](./assets/ScreenShot-destop.png)
![](./assets/ScreenShot-tablet.png)
![](./assets/ScreenShot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/aavv8931/pod-request-access-landing-page)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I have been learning for HTML and CSS for a while; but I am trying to master it. I belive that this project among my others is the one that is the closet to design. Also, something new I implement is JS email validation as you can see below.

To see how you can add code snippets, see below:

```js
    let validate = function(event){

      event.preventDefault();

      if(email.value == '' || !validation.test(email.value)){
        error.style.display = 'inline'

        return false
      }

      return true
    }
}
```

## Author

- Frontend Mentor - [@aavv8931](https://www.frontendmentor.io/profile/aavv8931)
- Twitter - [@aavv89](https://www.twitter.com/aavv89)