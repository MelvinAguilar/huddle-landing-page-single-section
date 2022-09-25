# Frontend Mentor - Huddle landing page with single introductory section solution

![](./design/screenshot.png)

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules

### Useful resources

[CSS background Property](https://www.w3schools.com/cssref/css3_pr_background.asp) 

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── bg-desktop.svg
│   │   ├── bg-mobile.svg
│   │   ├── favicon-32x32.png
│   │   ├── illustration-mockups.svg
│   │   └── logo.svg
│   └── sass
│       ├── abstracts
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _buttons.scss
│       │   ├── _heading.scss
│       │   └── _horizontal-list.scss
│       ├── layout
│       │   ├── _footer.scss
│       │   ├── _header.scss
│       │   └── _info-section.scss
│       └── main.scss
├── design
│   ├── active-states.jpg
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   ├── mobile-design.jpg
│   └── screenshot.png
├── index.html
└── README.md
```