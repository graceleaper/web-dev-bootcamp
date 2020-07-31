# Classes vs. Ids

- The `id` selector is similar to the `class` selector, but there is a difference

- In HTML file:
```
<h1 id="heading">Hello world</h1>
```
- In CSS file:
```
/***** ID SELECTORS *****/
#heading {
    color: blue;
}
```
- To target the id with the value of 'heading', use the pound, or hash, symbol followed by the value we gave it in our HTML file
- Notice that if we had the following in the same CSS file...
```
h1 {
    color: red;
}
```
- ... the #heading overrides the h1 styling. *** Styles with class and id selectors overrride tag selectors
- When should use you classes and when should you use id's?
- You can only have one instance of an id on a single HTML file
    - So on a single file, you can only have one "heading" id. But you can have different id's on an HTML page
- Notice that you'll probably only have one h1 on a page anyways
-  Use `class` to group to related elements that you wanted to have the same styling
    - Notice textbook pages or newspaper layouts that have the same styling for certain features
- *** Any HTML element can have more than one class, but only one id
```
    <img class="broccoli orange-frame" src="broccoli.png" alt="broccoli">
```
- If you want multiple classes for an element, you need the separate the classes with a single space
    - Can't do this with id's – can't have more than one id at a time
- Will rarely use id's
```
    .broccoli {
        background-color: red;
    }

    .orange-frame {
        border-color: orange;
        border-width: 5px;
    }
```

- Pseudoclasses
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