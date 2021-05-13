# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Designing a 3-column preview component using HTML and CSS.

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover states for interactive elements

### Screenshot

![](./project-screenshots/mobile-version.jpg)
![](./project-screenshots/web-version.jpg)

### Links

-   Solution URL: [Add solution URL here](https://github.com/gowthamss/css-3column-preview-card/)
-   Live Site URL: [Add live site URL here](https://gowthamss.github.io/css-3column-preview-card/)

## My process

If I talk about my process or approach to this solution, I always start with the mobile first approach so it will be easier to move to web version. As I get the starter code, I started with HTML markup, because if I figure out how can elements be placed and what classes I can apply to reduce the effort of writing more CSS.

After I structured my HTML, there are actually 2 breakpoints given in the problem guide. So I first wrote css for the elements that will look same in all the resolutions. This approach avoided me writing styles for every breakpoint. Then I applied the layout changes for each breakpoint. Simple and cool.

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   CSS Grid
-   Mobile-first workflow

### What I learned

Before this challenge, I never used CSS grid. So, in this challenge I used it and it saved me a lot of extra css and also thinking of writing CSS. I definitely recommend anyone who is working with CSS, learn CSS grid.

And also I recollected my knowledge of semantic elements.
Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

Some CSS I like in this challenge:
--> Mobile

```css
.container {
    display: grid;
    grid-template-columns: 1fr;
    grid-auto-rows: 1fr;
}
```

--> Web

```css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-auto-rows: 450px;
}
```

### Continued development

I will for sure be using CSS grid for my upcoming projects.

### Useful resources

-   [Example resource 1](https://www.w3schools.com/html/html5_semantic_elements.asp) - This is good resource to refresh your understanding semantic markup.

## Author

-   Frontend Mentor - [@gowthamss](https://www.frontendmentor.io/profile/gowthamss)
-   Twitter - [@Gowthamss15](https://twitter.com/gowthamss15)
