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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [FrontEnd Mentor](https://www.frontendmentor.io/solutions/responsive-qr-code-component-solution-GkW17wF0hF)
- Live Site URL: [Page](https://diogoluxa.github.io/frontend-mentor-qr-code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned more about the importance of writing HTML that respects accessibility principles. I tried to maintain good semantic structure, used BEM‑style classes, and defined CSS variables to keep a consistent system of colors, sizes, and spacing. This made my styling work much easier.

```html
<div class="card__content">
  <h1 class="card__title">
    Improve your front-end skills by building projects
  </h1>
  <p class="card__description">
    Scan the QR code to visit Frontend Mentor and take your coding skills to the
    next level
  </p>
</div>
```

```css
:root {
  /* Colors */
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);
  /* Container */
  --container-mobile: 375px;
  --container-desktop: 1440px;
}
```

### Continued development

I plan to keep learning about accessibility and to write HTML that is increasingly clean and accessible.

### AI Collaboration

I used AI at the end to review my code and point out accessibility improvements and better class naming. I used ChatGPT for that.

## Author

- Frontend Mentor - [@DiogoLuxa](https://www.frontendmentor.io/profile/DiogoLuxa)
