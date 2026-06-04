# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)ї

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Pure CSS
- CSS Flexbox
- Responsive Web Design principles
- Flexbox

### What I learned

During this project, I learned how to create a cool image overlay effect. I discovered how to use `position: relative` on a parent container to act as an anchor, and `position: absolute` on the child element to make it sit perfectly on top of the image.

I'm really proud of figuring out how to trigger a hover effect on a child element when hovering over its parent:

```css
.image-container:hover .overlay {
    opacity: 1;
    cursor: pointer;
}
```

### Continued development

In future projects, I want to focus on refining my skills in the following areas:

- **Accessibility:** While I added hover states for mouse users, I want to learn more about adding proper `:focus-visible` states so that interactive elements are fully accessible to keyboard users.
- **CSS Grid Layouts:** I used Flexbox extensively for aligning items in this project. Moving forward, I want to explore CSS Grid to see how it compares to Flexbox for building more complex page structures.
- **Advanced Animations:** I enjoyed creating the hover overlay effect using opacity and basic transitions. Next, I plan to dive deeper into the `transform` property to create smoother, more dynamic UI interactions (like scaling or translating elements).

## Author

* GitHub - [Dubets-Ivan](https://github.com/Dubets-Ivan)
* Frontend Mentor - [@Dubets-Ivan](https://www.frontendmentor.io/profile/Dubets-Ivan)