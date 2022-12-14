# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  <!-- - [What I learned](#what-i-learned) -->
  <!-- - [Continued development](#continued-development) -->
  <!-- - [Useful resources](#useful-resources) -->
- [Author](#author)
<!-- - [Acknowledgments](#acknowledgments) -->

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Esse projeto seria um modelo de um site de notícias 

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
<!-- - **Bonus**: Toggle the mobile menu (requires some JavaScript) -->

### Screenshot

![web screenshot](./assets/images/Screenshot.png)

![mobile screenshot](./assets/images/screenshot-mobile.png)


### Links

- Solution URL: [GITHUB](https://github.com/victoraamlima/news-homepage-main)
- Live Site URL: [GITHUB - pages](https://victoraamlima.github.io/news-homepage-main/)

## My process

Eu primeiramentre construi todo o HTML e depos passei para o CSS.

Inicialmente eu usei o Display Grid para dividilo em 6 partes:

```css
 grid : "header" "header"  
        "main" "aside"
        "footer" "footer";
```
Porem percebi que ficaria mais facil alinhar todos os elementos se eu utilizase o Grid dessa forma:

```css
 grid: "header header header"
       "main-image main-image aside"
       "main-h main-text aside"
       "top-1 top-2 top-3";
```
![web screenshot - Grid](./assets/images/screenshot-grid.png)

Assim alinhando todos os elementos da pagina sem muitas dificudades

Alem disso utilizei o Display Flex nos elementos menores

Tive um pouco de dificuldade de fazer o sombreado ao lado do menu Hamburguer, devido eu não ultilizar JS nesse projeto, mas encontrei um jeito.

![web screenshot - menu open](./assets/images/screenshot-menu-open.png)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
<!-- - Mobile-first workflow -->
<!-- - [React](https://reactjs.org/) - JS library -->
<!-- - [Next.js](https://nextjs.org/) - React framework -->
<!-- - [Styled Components](https://styled-components.com/) - For styles -->

<!-- **Note: These are just examples. Delete this note and replace the list above with your own choices** -->

<!-- ### What I learned



```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.** -->

<!-- ### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.** -->

## Author

- Website - [Victor Lima](https://github.com/victoraamlima)
<!-- - Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername) -->
<!-- - Twitter - [@yourusername](https://www.twitter.com/yourusername) -->

<!-- **Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.** -->

<!-- ## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.** -->
