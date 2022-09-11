# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

### Links

- Solution URL: [Solution]()
- Live Site URL: [Live site]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Struggled a bit to setup the background pattern and used transform property to resolve this problem.

```html
<img src="/assets/bg-pattern-top.svg" alt="" class="top" />
<img src="/assets/bg-pattern-bottom.svg" alt="" class="bottom" />
```

```css
.top {
  position: absolute;
  transform: translate(-50%, -45%);
  width: 100%;
}

.bottom {
  position: absolute;
  transform: translate(44%, 49%);
  width: 100%;
}
```

## Author

- Frontend Mentor - [@DEEPAK-tech40](https://www.frontendmentor.io/profile/DEEPAK-tech40)
