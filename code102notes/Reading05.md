
### Chapter 10: Introducing CSS

- CSS is a system for styling HTML sheets
- it helps to imagine a box around each HTML element
- a CSS statement begins with a selector, and is followed by a declaration in brackets
- a seclector names the kind of HTML box to modify
- a declaration is a list of instructions on how to modify the box

#### Example Statement:

h1, h2, h3 {
    font-family: Arial;
    color: yellow;
}

- h1, h2, and h3 are heading selctors
- the declaration has two statemtns, one for the font of the text, and one for the color of the text

#### External/Internal CSS

- one way to use CSS is to use a <link> tag in the head of the page that links an external CSS file
- that CSS file will have statements like the above example
- the other way to use CSS is to embed a style tag on a page 
- the cheat sheet below does a great job at giving examples of different CSS statements and how to use them within pages of code

[Click Here](https://htmlcheatsheet.com/css/) for a CSS cheat sheet.



### Chapter 11: Color


- there are many ways to select color in a CSS statement
- you can use the color's name (from 147 recognized names)
- you can use a hex code
- you can use RGB values, format (red, green, blue)

h1 {
    color: MediumAquaMarine
    color: #66cdaa (hex code)
    color: rgb(102, 205, 170) 
}

[Click Here](https://www.w3schools.com/colors/colors_picker.asp) for a CSS color selector.



[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)