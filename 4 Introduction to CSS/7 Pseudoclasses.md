# Pseudoclasses
- Search on mdn or w3 schools for "css pseudoclasses"
- Notice that you see colons before pseudoclasses
- HTML elements can have different states
    - So when your mouse is over a text or image, the HTML element is actually in a different state
    - I can change the CSS based on the current state (so if we're hovered over or not hovered over an element)
- A really common pseudoselector  is `:hover`
    - See mdn or w3 school docs
```
    img:hover {
        background-color: gold;
    }

    /* probably won't change the color of the h3 though... most developers will change  the CSS of text when it's a link */
    h3:hover {
        color: purple;
    }

    a:hover {
        color: turquoise;
    }
```
- Sample code on using `:hover` selector to make hidden elements visible upon hovering: https://replit.com/@GraceLee19/Pseudoclasses#style.css