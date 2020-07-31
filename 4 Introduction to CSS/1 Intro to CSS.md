# Intro to CSS
- CSS (Cascading Style Sheets)
    - Used to style markup language, HTML
- Change our websites to look stylish, and instead of something like from the nineties!

### Colors

- Creating a personal site
- seanhalpin.io

```
/* can use keyword values */
background-color: red;

/* can use keyword values */
background-color: ##bbff00
```
- Google: "css colors mdn" for a chart of colors
- Color schemes on: colorhunt.co

### CSS Properties

```
body {
    background-color: red;
}
```

```
hr {
    background-color: white;
}
```
- Above code doesn't work
- Even before we create a CSS file, there are default or existing styles of our HTML elements done by our browser
- Google: "browser default css"
    - See W3 Schools for a list of HTML elements and their default styles
- Notice for `hr`, there are margins and `border-style`, with a default value of `inset`
    - Google: "border-style css"
    - Several keywords
    - Notice that `inset` creates an embedded effect
- Set the border-style to 'none' now
    - All the hr's disappear, since, according to the docs, 'none' defines no border
- can set height and width to the hr

```
hr {
    background-color: white;
    border-style: none;
    height: 2px;
    width: 30% /* instead of 100px */
}
```
- Avoid pixels for widths, since other people may be viewing your site on a phone or iPad. This means your line may end up looking really long on a smaller screen size, but you want the line to scale / shrink down on a smaller screen with less pixels on a width
- hr will always be 30% of the window's width
- Let's change our hr to look like the dotted line from Sean Halpin's site:
    - Want to have a border-style of "dotted" (see mdn docs)
    - 

```
hr {
    background-color: white;
    border-style: dotted;
    height: 2px;
    width: 30% /* instead of 100px */
}
```
- We have a 4 sides with dots over our hr
    - This is the case since we have a height of 2px. So remove the border's height

```
hr {
    background-color: white;
    border-style: dotted;
    width: 30% /* instead of 100px */
}
```
- We'll still have an overlapping/squished 4-sided border though
- See the "Syntax" section of MDN docs on border-style (https://developer.mozilla.org/en-US/docs/Web/CSS/border-style)
    - We're getting the overlapped borders, since one value will apply to **all four sides**

```
hr {
    background-color: white;
    border-style: dotted none none;
    width: 30% /* instead of 100px */
}
```
- We now only have a single row of dots
- We can also just do the following:
```
hr {
    border-style: none;
    border-top-style: dotted;
    width: 30% /* instead of 100px */
}
```
- The same affect as the previous code block
- Also get rid of background-color, since we don't have a background being surrounded by a 4-sided border

```
hr {
    border-style: none;
    border-top-style: dotted;
    width: 30% /* instead of 100px */
    border-color: grey;
    border-width: 5px;
    /*
        try 20px, then 10px at first
        border-width sets the width or size of each dot
    */
}
```