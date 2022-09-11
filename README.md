# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

![desktop-preview](https://user-images.githubusercontent.com/94350356/189515629-f8d4a3df-680c-4932-b970-a7b64d8375c2.jpg)


### The challenge

- Build out the project to the designs provided

### Screenshot

Desktop-View:

![2022-09-11 (3)](https://user-images.githubusercontent.com/94350356/189515672-2d26bb42-bc38-4787-b1e7-d57ee75f06ce.png)


Mobile-View:

![2022-09-11 (2)](https://user-images.githubusercontent.com/94350356/189515658-4ddd7089-0ab0-4c13-a687-41565c1d9e66.png)


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/profilecardcomponent-Bb09Y4HqvC)
- Live Site URL: [Live site](https://deepak-tech40-profilecard.netlify.app)

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
