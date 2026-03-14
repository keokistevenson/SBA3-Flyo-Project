# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot


#### Mobile Sreenshot
<p align="center">
  <img src="./images/screenshot.jpg" width="300">
</p>

#### Desktop Sreenshot
![](./images/screenshot2.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap
- CSS Grid

### What I learned

The standard way of linking CSS files in HTML is ridiculous. It hides the <title></title> tag.  
ChatGPT suggested an alternative that I like. 😀

I learned to make sure my style sheets are placed after the links for Bootstrap because Bootstrap will overwrite my code.

I learned that I can make a nice progress bar using HTML and CSS.

To see how you can add code snippets, see below:

```html
<div id="control" class="card p-4 shadow-lg rounded-4 rounded-end-circle rounded-bottom-4"> </div>
```
```css
.progress {
    background: conic-gradient(hsl(229, 57%, 11%), hsl(229, 7%, 55%));

    margin-bottom: 15px;
    height: 20px;
}
```

### Continued development

I want to give Tailwind a try. I don't care much for Bootstrap. 😀

I'm also looking forward to using some dropdown menus. I've not done any accordians, hamburger signs, or carousels yet. I'd like to give these a try. Breakpoints look interesting. Containers, validation, and using some especially SASS might be a great step forward.

### Useful resources

- https://getbootstrap.com/

Don't go to bootstrap.com

### AI Collaboration

I did the vast majority of this by myself. I didn't add the little triangle part on the "185 GB LEFT" bubble because I didn't what to risk giving ChatGPT credit for my hard work.

AI was helpful in letting me know I was wasting my time trying to use Bootstrap. 

## Reflection
- Challenges you encountered during the project.
  Wasting time trying to get Bootstrap to work. It would have been a lot easier to have used CSS.  For example I thought I would try absolute positioning using bootstrap as it seemed like it might be easy. It was a complete waste of time. I ended up having to implement it myself using CSS.

  Bootstrap is good for rapid prototyping and if you just want to try something quickly. I prefer CSS. This is too sloppy and carries too much baggage. One small change can have several unintended side effects.

  Paul said he likes emojis in our reflections because it reminds him of AI 😀

- Your approach to solving these challenges.
  I tried to find something related to bootstrap first to see if i could implement it.

  While it is not a perfect solution, I'm proud I was able to use Bootstrap to create a nearly perfect border radius. I was afraid it wasn't going to turn out right and i would have to abandon this approach for CSS but I think it pulled it off and got close enough.

  ```html
    <div id="control" class="card p-4 shadow-lg rounded-4 rounded-end-circle rounded-bottom-4"></div>
  ```

- Improvements you would make if given more time.
  None! The only way to make this better is to use more CSS.


## Author

Keoki M. Stevenson