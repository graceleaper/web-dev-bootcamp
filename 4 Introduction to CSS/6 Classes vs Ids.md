# Classes vs Id's

## Id Selector
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

## Class Selector
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
- What if I have a bunch of div's or p tags, but I don't want all my div's or all my p tags to have the same background-color and color? Can use `class` selector to make only certain div's or certain p's have a specific style

![medium article](images/8.png)

- Notice on websites like medium.com and similar ones, there's a section about the writer of the article underneath the post. Also notice that the paragraph inside the author section is styled differently than the paragraphs from the article above. So we wouldn't want to just style `p` tags. Or else the styling would be the same on the article and author section paragraphs.

```

<h1>The Tech Corner</h1>

    <h2>Productivity Apps for School</h2>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Enim lobortis scelerisque fermentum dui. Mattis nunc sed blandit libero volutpat sed cras. Placerat in egestas erat imperdiet. Tortor at risus viverra adipiscing at in. Faucibus ornare suspendisse sed nisi lacus sed.</p>

    <div>
        <h3>Written by Grace Lee</h3>
        <img src="grace-headshot.jpg" width="50%">
        <p class="writer-bio">Computer Science Teacher at The Buckley School. Dedicated to helping young people explore the full potential of what they could learn and be through technology.</p>
    </div>

    <h3>My Time at the Tony Stark Internship</h3>
    
    <p>Sed nisi lacus sed viverra tellus in. Ornare aenean euismod elementum nisi quis eleifend quam adipiscing. Suspendisse faucibus interdum posuere lorem. Sagittis id consectetur purus ut faucibus pulvinar. Ut diam quam nulla porttitor. Malesuada fames ac turpis egestas sed tempus urna et pharetra. Tortor posuere ac ut consequat. Cursus euismod quis viverra nibh cras pulvinar. Ut tellus elementum sagittis vitae et leo. Nunc non blandit massa enim nec dui.</p>

    <div>
        <h3>Written by Peter Parker</h3>
        <img src="peter-parker-headshot.jpg" width="50%">
        <p class="writer-bio">High school student, living in Queens, NYC. Science and tech enthusiast. The people who inspire me the most are Mr. Tony Stark and Spiderman.</p>
    </div>

```
- In the above code sample, we can have the same `class` name for the `p` tag within the div, in this case:  `writer-bio`. This will make the style for the `writer-bio` paragraph be different than the style from the other paragraphs that were used to write the actual article posts
- Notice that even though the `p` tags may styled have specific styles, using the `class` selector will override the styles for the `p` tag. So if we want to stay organized, we can apply classes to our article paragraph(???)
- Note: We can use class on any opening HTML tag. If we really wanted to, we can do the following:

```
<p>Welcome to <em class="location">The Buckley School</em></p>
```
- And we can use `color`, `font-size`, etc. on the `location` class