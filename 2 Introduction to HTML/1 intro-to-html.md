# Introduction to HTML

- Browsers (Chrome, Safari, Firefox) have the job of interpreting our files, like HTML, and use them to display a website

```
<head>
    <title>Hellow</title>
</head>

<body>
    <h1>Hello World!</h1>
</body>
```

- Pass the above code to our browser, which will display it on our website that we requested
- Title of the website is on the tab
- The big heading "Hello World!" is displayed in the body of our website

- HTML is the foundation of all websites
- You won't see websites with just CSS or JS files
- But you can create websites with just HTML

- HTML: HyperText Markup Language
    - Note the word "markup". This is based off the idea of marking up manuscripts for editors
        - Markups used to specify changes for authors or structures for publishers
        - Squiggly lines should be printed in bold
        - Circled words to be italicized
        - See image on a guide to copyediting marks: https://s3.nybookeditors.com/blog/2013/06/image-copyediting-marks.jpg
    - With HTML, we can specify the structure of our content (so our text and images)

- Go to codepen.io
    - No need to sign-up
    - Can see the live version of our website
    - Can minimize CSS and JS editors
    - Can head over to a copy of _The Adventures of Sherlock Holmes_ by Arthur Conan Doyle on the Project Gutenberg
    - Can view the book as plain text or in HTML. Notice that plain text version of the book has absolutely no structure
    - Will replicate the more human readable, HTML version of the book in codepen
    - Copy and paste the title and author name into codepen
    - Notice in the codepen's live version of the website, there is no structure to the text
    - Start adding HTML to our text
    - Notice that title is largest section of the HTML version of the book
    - Surround the title in `<h1>` tags
        - Tags start with opening angle bracket and ends with closing angle bracket
        - Closing tag will have forward slash after the opening angle bracket
        - If we don't have closing tags, our browser will think that all the content, from beginning to end, needs to be in `h1` tags. But we don't want our author name to be so big
        - Author name on HTML version of the book seems to be smaller than our book title
    - Use `h2` tags to create a slightly smaller heading. Suggests this heading is of less importance than the title
    - Wrap the word "by" in `h3` tags
    - *** Heading tags get smaller as the number goes up
        - `h6` is the smallest font size for the heading element

    - How do I know that there only 6 heading sizes?
    - Good time to introduce documentation
         - Important to know about documentation during your journey as a web developer
         - Even web developers working at companies need documentation, or documents with key terms and explanations for syntax
         - So we're going to be really good at Googling in this class
         - In Google, type the following search terms: "headings html mdn"
         - Note: mdn stands for Mozilla Developer Network, the same people who created Firefox
         - Even have example code snippets
         - Another source / website with documentation other than MDN is W3 Schools
         - So Google: "headings html w3 schools"
         - Don't have to understand everything in the docs (which I'll probably say instead of the word documentation from time to time)
         - Can also use devdocs.io, which uses information from MDN, but in simpler form
         - If we want spacing in between text, HTML doesn't recognize when we just type "Enter" several times
         - Need to use an HTML element: `<br>`, which is called a line break
         - Unlike 99% of other tags, we don't need a closing tag, and no forward slash
