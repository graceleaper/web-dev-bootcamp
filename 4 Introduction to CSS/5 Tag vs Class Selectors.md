# Tag vs. Class Selectors

- emojipedia.org is a good websit to find images of emojis on different devices (Apple, Google, Facebook, etc.)
- Search for an image, then right-click on "Copy Image Address", which can be used as the src in an image tag in your HTML file

```
img {
    background-color: red;
}
```
- The above code will target all img elements
- So if I put in a second img from emojipedia, the background of that image will automatically be red

- In our HTML file:
```
<img class="bacon" src="bacon.png" alt="bacon">
<img class="brocolli" src="brocolli.png" alt="brocolli">

```
- The "class" attribute allows us to differentiate between different HTML elements
- Note: add comments in CSS with /* */

```
/****** TAG SELECTORS ******/
h1 {
    color: red;
    font-size: 200px;
}

/****** CLASS SELECTORS ******/
.bacon {
    background-color: green;
}

.brocolli {
    background-color: red;
}

```
- Target a class in CSS file by starting off with a period, and then add the name of the class from the HTML file
- So even though we have two img elements, they each have different class names. Think of classes as like a label