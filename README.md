# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](.design/card-component-solution.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS components
- CSS Grid
- Mobile-first workflow


### What I learned

I learned four (4) new things by working on this challenge:

1. Using the root CSS pseudo-class. It helps defining the colors to be used in the project and reduce mistakes in term of memorizing and key-in the hex code of the colors.

```css
:root {

  --white: #ffffff;
  --black: #000000;
  --darkcyan: #3C8067;
  --cream: #F2EBE3;
  --darkblue: #1C232B;
  --darkgrayishblue: #6C7289;
  --mediumlightgrey: #707176;
}
```

2. Using the universal selector to provide a seamless look to the page without further CSS styling.

```css
*, a {
  color: var(--black);
  font-family: 'Montserrat', sans-serif;
  font-size: 12px;
  font-weight: 500;
  margin: 0;
  text-decoration: none;
  cursor: pointer;
}
```

3. CSS grid. The occasional use of using margin to push the grid involved to the centre has been quite a new insight to what can be done using CSS grid.

4. The usage of media query to apply changes to the page once the screen of the size differs.


### Continued development

Things I'd like to focus on moving forward from this project/challenge:

1. More projects/challenges using CSS grid and flexbox.

2. Further use of media query in future projects/challenges.

### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=9zBsdzdE4sM&t=472s) - This helped me understand how grid and the codes linked to it can be used.
- [Example resource 2](https://www.youtube.com/watch?v=PNK6VGFquao&t=688s) - This helped me understand and see actual applications of CSS grid on an actual project.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Nur Aina Balqis Mohamad Rosidek](https://github.com/nabbysidek)
- Frontend Mentor - [@nabbysidek](https://www.frontendmentor.io/profile/nabbysidek)
- Instagram - [@codewsalem](https://www.instagram.com/codewsalem/)



## Acknowledgments

I'd like to thank CoderCoder (https://www.youtube.com/c/TheCoderCoder) and Web Dev Simplified (https://www.youtube.com/c/WebDevSimplified) on Youtube for the swift and easy to understand explanation on CSS grid. I'd also like to thank Miss Natasha (https://medium.com/@nknuranathunga) for giving me inspiration and idea to solve the solution as well. 
