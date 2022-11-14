# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
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

### Screenshot

![](./screenshot.png)

### Links

<!-- - Solution URL: [Add solution URL here](https://your-solution-url.com) -->
- Live Site URL: [https://gd-qr-code-component.netlify.app/](https://gd-qr-code-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- [TailwindCSS](https://tailwindcss.com/)
- Flexbox
- Mobile-first workflow

### What I learned

I used align-items: center and justify-content: center in both an outer and inner flexbox container so the QR code component is centered in the viewport.

Outer flexbox:
```html
<body class="flex h-fit items-center justify-center">...
```

Inner flexbox:
```html
<div class="flex items-center justify-center">...
```

## Proposed solution
```html
<body class="flex h-fit items-center justify-center bg-blue-100">
  <div class="flex flex-col">
    <div
      class="flex items-center justify-center bg-white w-auto max-w-xs mx-4 my-24 rounded-2xl p-4 shadow-2xl shadow-neutral-900/10">
      <div class="flex flex-col">
        <img class="rounded-lg mb-6" src="./images/image-qr-code.png" alt="QR code">
        <h1 class="text-center text-xl font-bold px-4">Improve your front-end skills by building projects</h1>
        <p class="text-center text-xs py-4 px-8 text-neutral-400">Scan the QR code to visit Frontend Mentor and take
          your coding skills to the next level</p>
      </div>
    </div>
  </div>
</body>
```

## Continued development

Areas of focus for the future include minimising the vertical padding that is used to control text layout getting too out of hand. It's easy to add too many padding directives if not careful.

### Useful resources

- [Tailwind Docs - Justify content](https://tailwindcss.com/docs/justify-content)
- [Tailwind Docs - Align items](https://tailwindcss.com/docs/align-items)

## Author

- Website - [A Goodreds](https://goodreds.net)
- Frontend Mentor - [@goodreds](https://www.frontendmentor.io/profile/goodreds)
- Twitter - [@goodreds](https://www.twitter.com/goodreds)

## Acknowledgments

n/a
