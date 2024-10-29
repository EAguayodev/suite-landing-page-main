# Frontend Mentor - Suite landing page solution

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Github](https://github.com/EAguayodev/suite-landing-page-main)
- Live Site URL: [Vercel](https://suite-landing-page-main.vercel.app/)

## My process
1. Planning the Structure: I started by carefully planning the HTML structure, sketching out the document layout to ensure it would be organized and adaptable for different screen sizes.

2. Researching CSS Properties: Next, I reviewed CSS properties on a reference page to decide on class names and styling approaches that would best support responsive design. This step helped me align class names with the styles required to achieve the design goals.

3. Implementing Desktop-to-Mobile Workflow: I used a desktop-to-mobile workflow, building the layout from the largest viewport and working down to ensure responsiveness on smaller screens.

4. Matching the Design Closely: Throughout, I focused on ensuring that the visual result closely matched the provided design, adjusting breakpoints and image sources to optimize the appearance across devices.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow


### What I learned

Ensuring Design Accuracy: Finally, I focused on matching the design closely, adjusting breakpoints and image sources as needed for optimal display on both portrait and landscape orientations.

To see how you can add code snippets, see below:

```html
  <picture>
    <source media="(min-width: 58rem)" srcset="assets/image-jeremy-large.webp">
    <source media="(max-width: 35rem)" srcset="assets/image-jeremy-small.webp">
    <source media="(max-width: 48rem)" srcset="assets/image-jeremy-small@2x.webp">
    <img class="testimonial-img" src="assets/image-jeremy-small.webp" alt="Jeremy Robinson">
  </picture>
```
```css
.btn-request-2:hover {
    background: linear-gradient(150deg, hsl(292, 76%, 54%) 0%, hsl(31, 100%, 65%) 100%);
}
```

### Continued development

To further strengthen my skills, I plan to complete as many junior developer challenges as possible over the next three months. These challenges will help me solidify foundational concepts, refine my approach to responsive design, and expand my experience with new techniques in HTML, CSS, and JavaScript. By consistently tackling these tasks, I aim to grow my proficiency and prepare for more advanced projects.

### Useful resources

- [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - This helped me for finding the picture element, and using the source and img elements to create responsive images.

## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@EAguayodev](https://www.frontendmentor.io/profile/EAguayodev/solutions)