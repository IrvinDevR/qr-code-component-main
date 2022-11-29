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

## Overview

### Screenshot
![image](https://user-images.githubusercontent.com/114030068/204470423-56efd521-8538-4795-8ec0-d2edda1f5efa.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/IrvinDevR/qr-code-component-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

First I created the html tags.:
- Added a <section>.
- Within the section, I nested two <div> one for the QR image and another for the description.
- Finally, inside the second "div" I nested an <h2> and a <p> with the values that FrontEnd Mentor gave me.
  
Then I started with the styles:
- For this I created a file "style.css" in which I introduced all the necessary styles.
- Set the margins and padding to zero.
- Initially formatted the html and the body.
- I gave the necessary sizes to the section, the image container and the description container.
- Added the image as the background of the image contender.
- And I formatted the texts.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
  
### What I learned

I learned to structure my html better. I found a simple way to enter all the elements that this little project required without introducing unnecessary tags.

```html
<section>
  <div class="containerImg"></div>
  <div class="containerDesc">
    <h2>Improve your front-end skills by building projects</h2>
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</section>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

* {
   margin: 0;
   padding: 0;
   box-sizing: border-box;
}

:root {
   --color-White: hsl(0, 0%, 100%);
   --color-Light-gray: hsl(212, 45%, 89%);
   --color-Grayish-blue: hsl(220, 15%, 55%);
   --color-Dark-blue: hsl(218, 44%, 22%);
   --ff-Outfit: 'Outfit', sans-serif;
}

html,
body {
   width: 100vw;
   height: auto;
   background-color: var(--color-Light-gray);
}

section {
   width: 320px;
   margin: 40px auto;
   height: 500px;
   background-color: aqua;
   border-radius: 20px;
   -webkit-border-radius: 20px;
   -moz-border-radius: 20px;
   -ms-border-radius: 20px;
   -o-border-radius: 20px;
   padding: 18px;
   background-color: var(--color-White);
   box-shadow: 1px 1px 5px rgb(207, 207, 207),
      -1px -1px 5px rgb(207, 207, 207);
}

.containerImg {
   width: 286px;
   height: 286px;
   border-radius: 10px;
   background-image: url(images/image-qr-code.png);
   background-position: center;
   background-size: cover;
   background-repeat: no-repeat;
   -webkit-border-radius: 10px;
   -moz-border-radius: 10px;
   -ms-border-radius: 10px;
   -o-border-radius: 10px;
}

.containerDesc {
   width: 260px;
   margin: 0 auto;
   height: 178px;
   display: flex;
   flex-direction: column;
   justify-content: space-evenly;
   text-align: center;
   font-family: var(--ff-Outfit);
}

.containerDesc h2 {
   color: var(--color-Dark-blue);
   font-size: 22px;
}

.containerDesc p {
   font-size: 15px;
   color: var(--color-Grayish-blue);
}
```

### Continued development

Something I'd like to learn more about is the properties and values that can be used on an image so I can size it to what I need.

### Useful resources

- [Page Ruler](https://chrome.google.com/webstore/detail/page-ruler/jcbmcnpepaddcedmjdcmhbekjhbfnlff) - This extension helped me to be able to measure the pre-design in order to be able to extract more exact measurements from the mockup.

## Author

- LinkedIn - [Rubén Mantilla Quiroz](https://www.linkedin.com/in/ruben-mantilla-desarrollador-frontend/)
- Website - [GitHub](https://github.com/IrvinDevR)
- Frontend Mentor - [@IrvinDevR](https://www.frontendmentor.io/profile/IrvinDevR)
- Twitter - [@DevRMQuiroz](https://twitter.com/DevRMQuiroz)
