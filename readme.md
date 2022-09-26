# Open Sea NFT

In the spirit of collaborating with designers, I saw a desgner post this design and i decided to bring it to life.

## Table of contents

- [Overview](#overview)
- [Screenshot](#screenshot)
- [Links](#links)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
This is a simple and well structured landing page foe open sea, a brand that allow users create, buy and sell NFTs. 
I have not worked on a similar concept in the past so it made devloping this project more intruiging. 


### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Have good experiemce while usung the website
- Easy navigation and control
- Implement micro interactions
### Screenshot
![](./dist/images/Screenshot%202022-09-26%20185524.png)

### Links

- Repo URL: [Add solution URL here](https://github.com/Rasheedatj/Open-Sea)
- Live Site URL: [Add live site URL here](https://rasheedatj.github.io/Open-Sea/)

## My process
I wrote the html and css for each section simultaneously, this is a technique that i find easier. I wrote all my variables and mixins before i started styling  in a partial.
I ensured that my codes are redeable incase of future refrence and for people who may wish to learn from it.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- SCSS
- Grid layout

### What I learned

- More on how to use grid to my advantage


```html

       
           <div class="box">
               <img src="./dist/images/collection_3.svg" alt="nft product">
               <div class="heading">
                   <h1>Faveshave honey <span>#09</span></h1>
               </div>

               <div class="owner_info">
                   <img src="./dist/images/avatar_3.svg" alt="owner avatar">
                   <div class="name">
                       <p class="glass">owned by</p>
                       <p class="name-capital">joan kid</p>
                   </div>
                   <div class="bid">
                       <p>current bid</p>
                       <p>5 eth</p>
                   </div>
               </div>

               <div class="footer">
                   <a href="#" class="gradient_btn">bid now</a>
                   <div class="history">
                       <img src="./dist/images/Vectortime.svg " alt="history">
                       <p>view history</p>
                   </div>
               </div>
           </div>
```

```css

        .pink_btn{
         @include flex(2rem);
         padding: 1.5rem;
            a{
                font-size: 2rem;
                text-decoration: none;
                color: $pinkbtntext;
            }
            i{
                font-size: 2rem
            }
        }

```



## Author
### Developer
- LinkedIn - [Rasheedat](https://www.linkedin.com/in/rashedat-jinadu-066078227)

- Twitter - [@Rashedatj](https://www.twitter.com/Rashedatj)

## Acknowledgement

### Designer
- Twitter - [@Only1Lara](https://twitter.com/Only1Lara?s=20&t=IMHeU3X0hXEaLZEENgt_uQ)