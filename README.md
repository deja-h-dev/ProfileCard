# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- Build out the project to the designs provided

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Using this [CSS Reset](https://meyerweb.com/eric/tools/css/reset/).

- body - will use bg pattern top & bottom SVGs, max width and max height 100vw and 100vh, maybe?
- div#card - will have a border radius of 10px, will position bg pattern svg to top, probably need to contain or cover the bg svg, display flex direction column. inside the #card:
  - img#userImg - border will be 2 or 3 pxs, round, solid, and white
  - div#user - user name and age is in same the p tag, name is wrapped in a span.bold, user location in separate p tag
  - div#userDetails - display flex row, inside #userDetails:
    - div.stats 3x -  number and stat is in the same p tag, number is wrapped in span.bold, br tag to give the numbers and stat name a separate line

- Started styling the background and learned a lot about using the background shorthand property. First of, I didn't even know you could have multiple background images! Second, when using multiple bg imgs, the background color has to be the last value for some reason or the whole property will be invalid.
- When I come back to this I have to figure out how to position the background images in the corners of the page.

### Built with

- Semantic HTML5 markup
- SCSS
- Mobile-first workflow
- Flexbox

### What I learned

- SASS is easy to set up! I installed it via CMD instead of via NPM like I was taught in a web dev course. SASS via CMD is easier for me. Though, I'm not a command line expert.
- Every time I fire up my project, I have to start SASS. In CMD I have to navigate to my stylesheets dir, watch my main.scss file for changes and output it to css\styles.css.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
### Continued development

- Q: What is srcset?

### Useful resources

- [CSS Reset](https://meyerweb.com/eric/tools/css/reset/) - 
- [Example resource 2](https://www.example.com) - 

## Author

- Frontend Mentor - [@deja-h-dev](https://www.frontendmentor.io/profile/deja-h-dev)
- Twitter - [@dejadev_](https://www.twitter.com/dejadev_)

## Acknowledgments

- 