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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Github URL](https://github.com/The-Lone-Druid/Product-preview-card-component)
- Live Site URL: [Deployed URL](https://the-lone-druid.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [TailwindCSS](https://tailwindcss.com/) - TailwindCSS CSS library

### What I learned

I learned how to use TailwindCSS to style the webpage. I also learned how to use the grid system in TailwindCSS to create a responsive layout.

To see how you can add code snippets, see below:

```html
<div class="grid grid-cols-12">
  <div class="col-span-6"></div>
  <div class="col-span-6"></div>
</div>
```

```css
.text-display {
  font-family: Fraunces;
  font-weight: bold;
  font-size: 2rem;
  line-height: 2rem;
}
```

```js
tailwind.config = {
  theme: {
    extend: {
      fontFamily: {
        sans: ["Montserrat", "sans-serif"],
      },
      colors: {
        "pure-white": "#ffffff",
        cream: "#F2EAE2",
        "aurometal-saurus": "#6C7289",
        "deep-aquamarine": "#3D8168",
        "deep-aquamarine-hovered": "#1A4032",
        gunmetal: "#1C232B",
      },
    },
  },
};
```

### Continued development

I will continue to use TailwindCSS in my projects to improve my skills in using the library. I will also continue to use the grid system in TailwindCSS to create responsive layouts.

### Useful resources

- [TailwindCSS Documentation](https://tailwindcss.com/docs) - This helped me understand how to use TailwindCSS to style the webpage. I really liked this pattern and will use it going forward.
- [Frontend Mentor](https://www.frontendmentor.io) - This is an amazing platform that helped me improve my skills in web development. I really liked the challenges and will continue using them to improve my skills.

## Author

- Website - [Zahid Shaikh](https://www.zahidshaikh.space)
- Frontend Mentor - [@The-Lone-Druid](https://www.frontendmentor.io/profile/The-Lone-Druid)
- Github - [The-Lone-Druid](https://www.github.com/The-Lone-Druid)

## Acknowledgments

I would like to thank Frontend Mentor for providing such an amazing platform to improve my skills in web development. I would also like to thank TailwindCSS for providing such an amazing library to style the webpage.
