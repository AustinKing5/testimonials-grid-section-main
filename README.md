# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)


## Overview
This is a Frontend mentor challenge I coded using Semantic HTML5 and Custom css.

### The challenge

The challenge is to build out this testimonials grid section and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Users should be able to:

-   View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screenshot%202022-09-29 020518.png)


### Links

-   Solution URL: [solution URL](https://www.frontendmentor.io/solutions/responsive-testimonial-page-using-html-and-css-grid-vTjdmqMMVW)
-   Live Site URL: [Live site](https://marvelous-macaron-633f2d.netlify.app/)

## My process

- I began the process by ensuring that all texts and images where in the right HTML tags
- I inserted the necessary class in my tags
-- I used <div></div> tags I am really comfortable with them at the moment when it comes to styling
- I linked my styles.css to my HTML (index.html) file.

-   For the styling, I used the CSS grid to help my layout the various sections.
    \-- The css grid is a new concept I'm hence the reason for choosing it.
-   I styled  my work from top to bottom.

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   CSS Grid
-   Desktop-first workflow

### What I learned

This project taught me responsiveness. Since I was learning css grid for the first time, it was important for me to learn how to make my elements responsiveness. For me, it was the highlight of the whole project when I was able to achieve that.

```css
@media (max-width: 375px) {
   body {
    max-width: 375px;
    margin: 0;
   }
  .container {
    display: grid;
    margin: 2em 1em;
    width: 100%;
    padding: 0;
   }

.testimonial-1 {
  grid-column: 1;
  width: 250px;
 }
.testimonial-2 {
  grid-row: 2;
 }

.testimonial-3 {
  grid-row: 3;
 }

.testimonial-4 {
  grid-column: 1;
  grid-row: 4;
}

.testimonial-5 {
   grid-row: 5;
   grid-column: 1;
  }
}
```

### Continued development

-   I am going to read more on the documentation of css grid. I am also going to study codes from other submitted solutions to learn how to write clean codes.


## Author

-   Website - [Augustine Aryeteh Asare](https://github.com/AustinKing5)
-   Frontend Mentor - [@AustinKing5](https://www.frontendmentor.io/profile/AustinKing5)
-   Twitter - [@aryetehasare](https://www.twitter.com/aryetehasare)
