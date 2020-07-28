# HTML Links and Anchor Tags
- Notice on Jon Kleinberg's website has a bunch of hyperlinks throughout his site
- HTML = HyperText Markup Language
- We talked about how "markup" means adding structure to our content, the words on our page
- Haven't talked about the "hypertext" part of HTML
    - Basically just a bunch of text documents that are linked together with hyperlinks
    - Click on a hyperlink, and it takes you to another document
    - That's what the HT part of HTML is about
- What are these hyperlinks/links made of?
    - Right click on a hyperlink and select "Inspect"
    - Bring up Google Chrome developer tools

```
<a href="google.com">Google</a>
```
- Notice above, the value of the href is the destination (or link) we want to get to. Then we have the "link text" in between the anchor tags

1) Add a hyperlink on my personal site. Suggest adding a hyperlink to my school's website

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <img src="...jpg" alt="grace lee">

    <h1>All About Grace</h1>

    <p>I'm a <em>computer science teacher</em> at <strong>The Buckley School in NYC</strong>.</p>

    <p>I was born and raised in New York. And I love coffee.</p>
    <hr>

    <h3>Education</h3>

    <ul>
        <li><a href="https://www.fullstackacademy.com/">Fullstack Academy of Code</a>: Software Engineerig Program<li>
        <li>Teachers College, Columbia Univesity: Master of Education</li>
    </ul>

    <h3>Hobbies</h3>

    <ol>
        <li>Digital drawing</li>
        <li>Watching Netflix</li>
        <li>HIIT at home</li>
    </ol>
</body>
</html>
```
- By default, the highlighted/purple text of the hyperlink means that we visited that website before. If we haven't visited it before, it will be blue

2) Add some links to your hobbies! Link to images or YouTube videos

3) Link to my own page
- Create a new file in directory called `hobbies.html`
    - Will be created in the same folder (or directory) as the index.html file
- Copy the hobbies section (from index.html) and paste to the hobbies.html file's body
- On index.html, create an anchor tag:

```
<a href="hobbies.html">My Hobbies</a>
```
- Will be directed to a new page on your website, with just your hobbies
- Now you can start building multiple pages on your website

- Challenge: create another page! Create a hyperlink on the index.html leading to your new page
    - Can create: contact page/details, fictional details, writing samples