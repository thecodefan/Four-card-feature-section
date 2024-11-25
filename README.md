# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.
## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/Screenshot%202024-11-25%20at%2019-03-46%20Frontend%20Mentor%20Four%20card%20feature%20section.png)

### Links

- Solution URL:(https://github.com/thecodefan/Four-card-feature-section)
- Live Site URL: https://thecodefan.github.io/Four-card-feature-section

## My process

Using a mobile first approach, i focused on putting the elements where they are needed, and adding style after.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Using flexbox in order to position the four cards in the way they are was challenging, but doign it with only flexbox was very interesting too.

```css
.proud-of-this-css {
  .boxesContainer {
    width: 1200px;
    height: 550px;

    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
  }
  .rowOne,
  .rowTwo,
  .rowThree {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    align-items: center;
    justify-content: center;
  }
  .rowTwo {
    gap: 20px;
  }
}
```

### Continued development

Though there is responsiveness for sizes of 375 below and above, further media queries for other sizes will be needed
