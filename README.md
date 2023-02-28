# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl/hub). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./phoneview%20screenshot.png)
![](./phone%20screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/namaganda-esther/News-Homepage)
- Live Site URL: [Add live site URL here](https://namaganda-esther.github.io/News-Homepage/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learnt how to properly structure the different divs for flex to properly work

To see how you can add code snippets, see below:

```html
     <section>
        <article>
          <div>
            <img src="./assets/images/image-web-3-desktop.jpg" alt="">
          </div>
          <div class="article-content">
            <div class="article-content-item1">
               <h1>The Bright Future of Web 3.0?</h1>
            </div>
            <div class="article-content-item2">
              <p>We dive into the next evolution of the web that claims to put the power of the platforms back into the hands of the people. 
                But is it really fulfilling its promise?
              </p>
              <button><a href="#">READ MORE?</a></button>
            </div> 
          </div>
        </article>
        <nav>
          <div>
            <h1>New</h1>
          </div>
          <div>
            <h4>Hydrogen VS Electric Cars</h4>
            <p>Will hydrogen-fueled cars ever catch up to EVs?</p> 
          </div>
          <hr>
          <div>
            <h4>Downsides of AI Artistry</h4> 
            <p>What are the possible adverse effects of on-demand AI image generation?</p>
          </div>
          <hr>
          <div>
            <h4>Is VC Funding Drying Up?</h4>
            <p>Private funding by VC firms is down 50% YOY. We take a look at what that means.</p>
          </div>
        </nav>
     </section>
```
```css
section{
    display: flex;
    display: -webkit-flex;
    flex-direction: row;
    flex-wrap: wrap;
}
```


### Continued development

I want to continue learning how add the responsiveness while using flexbox. with bootstrap, its quite easy to have a responsive layout unlike when your using flexbox or grid, so its something i want to look into

### Useful resources

- [W3schools](https://www.w3schools.com/) - This is my go to site incase of anything thats challenging, incase of any problems, they simplify things for me.
- [Google](google.com) - this ia nother tool is use incase of a challenge, just type in and i have different resources to look into.


## Author

- Website - [namaganda-esther](https://github.com/namaganda-esther)
- Frontend Mentor - [@namaganda-esther](https://www.frontendmentor.io/profile/namaganda-esther)
- Twitter - [@prudence_esther](https://www.twitter.com/prudence_esther)


## Acknowledgments

I want to thank myself for this milestone, knowing fully well that this is all me, i am excited. W3schools really helped alot in this project

