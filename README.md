# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Challenges](#challenges)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

!alt[](/assets/images/screenshot.png)

### Links

- Solution URL: [Solution URL here](https://github.com/dhayv/blog_card_html_css)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learned about using gap to seperate content instead of constantly using margin.

### Challenges

Deploying to GitHub Pages presented a series of challenges. Initially, the blog images that displayed correctly locally were not appearing when deployed. My troubleshooting process included several steps:

- Validation: I first checked to ensure the SVG file was valid.

- Configuration Adjustment: Added a `.nojekyll` file to bypass Jekyll processing, suspecting it might interfere with the rendering.

- Direct Link Test: Attempted to access the image via a direct link from GitHub Pages to isolate the issue, which helped identify additional web-related issues.

- Despite these efforts, the images still did not display correctly when linked through an `img` tag. The solution involved removing the `img` tag and directly embedding the SVG code into the HTML, followed by applying the necessary CSS styling. This method finally allowed the images to display correctly on the deployed site.

## Author

- Github - [Dhayv](https://github.com/dhayv)
- Frontend Mentor - [@Dhayv](https://www.frontendmentor.io/profile/dhayv)
