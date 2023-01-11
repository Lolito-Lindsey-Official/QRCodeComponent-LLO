# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Screenshot

qr-code-component-main/images/Screenshot 2022-12-25 at 09-13-06 Frontend Mentor QR code component.png

## My process

I took the visuals provided in the project file and utilized my prior knowledge of HTML, CSS custom properties, and Flexbox to get the project done. Throughout the process, I balanced design parity with originality to the best of my ability.

### Built with

- HTML
- CSS custom properties
- CSS Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Centering a container my molding its postion, margin, and it's overall orientation 
is one of the most effective code snippets I have learned so far.

``` 

    .container {
      width: 20rem;
      background-color: rgba(180, 180, 180, 0.5);
      padding: 1.5vh;
      border-radius: 5%;

      /* Centers the main container */
      display: flex;
      flex-flow: column;
      align-items: center;

      margin: 0;
      position: absolute;
      top: 50%;
      left: 50%;
      margin-right: -50%;
      transform: translate(-50%, -50%);
    }

```
### Continued development

I plan on integrating event listeners and manipulating the innerHTML via Javascript in future projects.

### Useful resources

- [Web Style Sheets
CSS tips & tricks](https://www.w3.org/Style/Examples/007/center.en.html) - This helped me for centering my QR code. I plan on using this resource in the future

## Author

- Github: https://github.com/Lolito-Lindsey-Official/Lolito-Lindsey-Official

## Acknowledgments

Shout to Brandon Sanders and David Bowen for the mentorship throughout this project.
