# 3-column-preview-card

## Table of contents
-   [Overview](#overview)
	-   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### Links

-   Card URL: [Vercel URl](https://3-column-preview-card-lonelyfirefly.vercel.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid

### What I learned

```css
*,
::before,
::after {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}
```
I used box-sizing: border-box; for the browser to account for any border and padding in the values I would specify for an element's width and height. This property typically makes it much easier to size elements. 
```css
.product {
	max-width: 920px;
	display: grid;
	grid-template-columns: repeat(3, 1fr);
	overflow: hidden;
	border-radius: 10px;
}
```
Here I used overflow:hidden property so that border-radius property worked. You see, you have to set overflow: hidden because otherwise the child div's overflow can give the impression that the border-radius isn't working.

```css
main {
		padding: 80px 20px;
		height: fit-content;
	}
```
I struggled with mobile version margins. The card would stick to screen borders. It took me a while to think of using height:fit-content.

### Continued development

In my future projects I really want to have more pracice with:
-   Flexbox
-   CSS Grid

### Useful resources

-   [W3Schools](https://www.w3schools.com/) - This one really helps me out every time I have difficulty with any css property.
-   [CS50](https://www.youtube.com/watch?v=NcoBAfJ6l2Q&ab_channel=CS50) - This YouTube channel has countless useful videos. I tend to watch it when I have troubles with Git.
-   [SmashingMagazine](https://www.smashingmagazine.com/2010/07/how-to-use-css3-media-queries-to-create-a-mobile-version-of-your-website/) - This one is an amazing article which helped me finally understand how To Use CSS3 Media Queries To Create a Mobile Version of Your Website.
## Author

-   LinkedIn - [Daniil Kalugin](https://www.linkedin.com/in/daniil-kalugin)
-   Twitter - [@BeingMyselfFlow](https://www.twitter.com/BeingMyselfFlow)
