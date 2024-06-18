# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page


### Screenshot


![screenshot desktop](https://github.com/Lo-Deck/Loopstudios-landing-page/blob/main/screenshot/Loopstudios%20landing%20page-desktop.png).
![screenshot mobile](https://github.com/Lo-Deck/Loopstudios-landing-page/blob/main/screenshot/Loopstudios%20landing%20page-mobile.png).
![screenshot mobile-menu](https://github.com/Lo-Deck/Loopstudios-landing-page/blob/main/screenshot/Loopstudios%20landing%20page-mobile-menu.png).



### Links

- Solution URL: [Repositories](https://github.com/Lo-Deck/Loopstudios-landing-page).
- Live Site URL: [Website](https://lo-deck.github.io/Loopstudios-landing-page/).



## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS
- Mobile-first workflow
- JS


### What I learned

I learned how to display a menu when you clcked on it. And set an overlay.

```js
if(menuMobile.style.visibility === '')
{
	buttonMenu.innerHTML = '<svg width="20" height="20" xmlns="http://www.w3.org/2000/svg"><path d="M17.778.808l1.414 1.414L11.414 10l7.778 7.778-1.414 1.414L10 				11.414l-7.778 7.778-1.414-1.414L8.586 10 .808 2.222 2.222.808 10 8.586 17.778.808z" fill="#FFF" fill-rule="evenodd"/></svg>';
	backgroundMenuMobile.classList.toggle('overlay');
 	menuMobile.style.visibility = 'visible';           
}
```


### Continued development

Learning from each challenge, I will continue to make website with JS and learning from different challenge from Front-end Mentor.


### Useful resources

- [Mozilla mdn](https://developer.mozilla.org/) - Very useful.
- [Utopia](https://utopia.fyi/) - To have a better responsive design.


## Author

- Frontend Mentor - [@Lo-deck](https://www.frontendmentor.io/profile/Lo-Deck)


## Acknowledgments

Thanks to Front-end Mentor and its community.
