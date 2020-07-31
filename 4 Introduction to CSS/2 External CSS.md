# External CSS

- Create a `style.css` file in directory
- On `index.html`, link to your css file:

```
<link rel="stylesheet" href="styles.css">
```
- Browser will take the styles.css file, and apply the styles to the specified HTML elements in our index.html file
- If we have multiple html pages, we can link the styles.css page to these html pages as well
    - All of our styles are applied across all the pages
    - And all we have to do is have a simple link in our HTML files that point to our "external style sheet"
- Challenge: select all h1 and h3 tags on your personal site, and change its color property to pink (or something else with a hex value)
    - Search on Google: 'change text color css'
- Changing text color (see w3 Schools):
    - Use `color` property
```
h1 {
    color: #66BFBF;
}

h3 {
    color: #66BFBF;
}
```

- Changes are reflected on all pages of our website
- Great job on getting it!
- Might be odd to have h1 and h3 be the same colors. Afterall, the reason we have different heading levels or sizes is because they have different uses (h1 for a major heading, h3 for subheadings)
    - Change up the h3 to a different color