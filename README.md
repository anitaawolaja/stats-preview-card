# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents


  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com) 


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to create a colour overlay using the CSS box-shadow property. The webpage that provided me with explnation on this was: https://www.w3schools.com/cssref/css3_pr_box-shadow.asp
The key think here is to use the inset value that changes the shadow from an outder shadoe (outset) to an inner shadow, and you can use that shadow to create a colour overaly of your image using RGBA.

This was the first time I worked with a Mobile-first workflow and i found that the proccess was a lot easier this way becasue I was building up as oppposed to building down, it made the process less complex, becasue all I had to do now was just add.


```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  background: url(images/image-header-mobile.jpg);
      box-shadow: inset 2000px 0 0 0 	rgb(170, 92, 219, 0.6);
      background-repeat: no-repeat; background-size: cover; 
    width:100%; height: 35vh; border-radius: 8px 8px 0 0;
}
```


### Useful resources

- [Example resource 1](https://www.internetingishard.com/) - This helped me to get a quick recap on how to use flexbox properly, in general a very usefull website for HTML and CSS concepts
- [Example resource 2](https://www.w3schools.com/cssref/css3_pr_box-shadow.asp) - A good explanation on how to use CSS box shadow property, which I used to creare a colout overlay on the image. 


## Author

- Frontend Mentor - [@anitaawolaja](https://www.frontendmentor.io/profile/anitaawolaja)

