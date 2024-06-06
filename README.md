# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [File Structure](#file-strucutre)
    -[Html Structure](#html-structure)
    -[CSS and tailwind](#css-and-tailwind)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgement](#acknowledgement)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
 I was able to create a social link card using html, css and tailwind.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-social-link-card-using-flexbox-and-tailwindcss-SOfE_jUuzI)
- Live Site URL: [Add live site URL here](https://caspgin.github.io/FrontEnd-Mentor-Challenge---Social-Link-Card/)

### File Structure

#### Html Structure

- body
    - main
        - profile
            - image
            - name
            - location
            - short description
        - links list
            - github
            - frontend Mentor
            - linkedIn
            - twitter
            - instagram

#### CSS and Tailwind 

- I used the [tailwind cli](https://tailwindcss.com/docs/installation) to build and use tailwind in my project. 
- There are 2 css files linked in the index.html named as follows:
    - input.css
    - output.css
- input.css contains all the custom css and tailwind directives.
- output.css contains the css build from tailwind.
    - I used the ```npx tailwind -i input.css -o output.css --watch``` command as instructed on the [tailwind website](https://tailwindcss.com/docs/installation).
- You can ignore package.json as it is only meant for installing tailwind as dev dependencies. For production output.css is used as I employ github pages for live service.




### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- TailwindCSS

## Author

- Website - [Abidali Sarangwala]
- Frontend Mentor - [@caspgin](https://www.frontendmentor.io/profile/caspgin)

## Acknowledgement
- This project has been updated and improved thanks to the awesome advice from [@gmagnenat](https://www.frontendmentor.io/profile/gmagnenat)


