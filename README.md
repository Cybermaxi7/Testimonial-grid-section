# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)




### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screenshot%20from%202022-10-25%2004-50-07.png)
![](./images/Screenshot%20from%202022-10-25%2004-50-35.png)
![](./images/Screenshot%20from%202022-10-25%2004-50-46.png)
![](./images/Screenshot%20from%202022-10-25%2004-50-58.png)
![](./images/Screenshot%20from%202022-10-25%2004-51-02.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learnt the concept of css grid
and the awesome power of grid-template-areas which makes it very easier to create layouts both for desktop and mobile
see some code snippets for grid-template-areas which i used for this challenge which i found amazing


```css
.testimonial__grid {
  width: 80%;
  display: grid;
  gap: 2rem;
  grid-auto-columns: 1fr;
  grid-template-areas:
  'one one two five'
  'three four four five'
}
```



### Useful resources

- [Resource from Youtube](https://www.youtube.com/watch?v=rg7Fvvl3taU) - This is a video by kevin powell which i found to help me during this challenge. I really liked this pattern and will use it going forward.



## Author

- Frontend Mentor - [@Cybermaxi7](https://www.frontendmentor.io/profile/Cybermaxi7)
- Twitter - [@Cybermaxi7](https://www.twitter.com/Cybermaxi7)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

I'd like to give credit to kevin powell because through his tutorials on css grid i was able to complete this challenge and learn so much on CSS GRID...