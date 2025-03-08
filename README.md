# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

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


## Overview

This is a HTML/CSS challenge that allowed me to practice fundamental skills. The end product is a single preview card, like those that we could find at any blog site. 

### The challenge

Users should be able to:

- See hover state for the title of the card.
- See how fonts adjust when the width of the screen changes.

### Links

- Solution URL: [Github repository](https://github.com/OmarReyesC/frontend-mentor-blog-preview-card)
- Live Site URL: [GH pages deployment](https://omarreyesc.github.io/frontend-mentor-blog-preview-card/)


### My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

### What I learned

This challenge helped me practice the process of bringing a Figma design to code. 
I also learned how to use .ttf files for fonts, since up to this point I had only used the regular Google Fonts links. 
Trying to make the font size adjust to the width of the screen without using media queries was an illuminating challenge as well. I ended up resorting to the clamp CSS method. For example:

```css
.text-preset-1 {
    font-size: clamp(1.25rem, 3vw, 1.5rem);
    line-height: 150%;
    font-weight: 800;
}
```

### Continued development

I intend to keep practicing my CSS and HTML skills. I still want to improve the way I create and use classes to ensure that I am making my code as concise and effective as possible. 


### Useful resources

- [clamp() Doc](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) - This is the documentation that taught me how to use the clamp CSS function to adjust the font-size as required.
- [Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This guide informed my usage of Flexbox in this challenge.


## Author

- Frontend Mentor - [@OmarReyesC](https://www.frontendmentor.io/profile/OmarReyesC)
- Twitter - [@reyesapiens](https://x.com/reyesapiens)


