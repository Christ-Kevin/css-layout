# css-layout
responsive web design with float, flexbox and grid

this is a summary to the [CSS Layouts: From Float to Flexbox and Grid](https://www.linkedin.com/learning/?u=82720546#:~:text=CSS%20Layouts%3A%20From%20Float%20to%20Flexbox%20and%20Grid). 

## Table of contents

- [Overview](#overview)
  - [The course](#the-course)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The course

- have a thorough knowledge of the handling of items and containers
- put into practice the knowledge already acquired in float, flexbox and grid

Users should be able to:

- Get better 

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Float
- Flexbox
- Grid
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

```html
 <nav>
        <h2>nav</h2>
        <a href="#main-content">skip navigation</a>
        <ul>
          <li>nav item</li>
          <li>nav item</li>
          <li>nav item</li>
          <li>nav item</li>
        </ul>
 </nav>
<main id="main-content">
        ...
</main>
```
```css
#####Float
.proud-of-these-css {
   aside {
        width: 25%;
        clear: none;
        /* so that the item can go on the right side */
        float: right;
    }
    
#####Flexbox
    .container {
    color: white;
    font-family: helvetica, arial, sans-serif;
    display: flex;
    flex-wrap: wrap;
}
header {
    background: skyblue;
    order: 1;
    flex: 1 0 100%;
}
}
```
set max-width for flexibility
mobile first befor min- and max-width


### Continued development

- responsive web design with css


## Author

- LinkedIn - [Christ Watat](https://www.linkedin.com/in/christ-k%C3%A9vin-touga-watat-32026712a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B8kg%2Bc3nQSpeLtRN4etFyNA%3D%3D)
- Frontend Mentor - [@Christ-Kevin](https://www.frontendmentor.io/profile/Christ-Kevin)
- Twitter - [@WatatK](https://www.twitter.com/WatatK)

