# What is the HTML Boilerplate?
- Create a project/folder/directory called "Personal Site"
- Memorize shotcuts. They will help you finish tasks a lot faster and will make your life a bit easier
- Create a file called `index.html`, which is what developes will usually name their homepage
- Every html file will have boilerplate code:
```
<!DOCTYPE html>
<html>
    <head>
    <meta charset="utf-8">
    <title></title>
    </head>

    <body>
    </body>
</html>
```
- In coding, we talk about boilerplate code frequently. It's a code template that can be reused in different coding projects
- Term comes from the days when printing presses would create heavy iron plates as their printing template
- These templates resembled small metal plate that identified the builder of steam boilers. Thus, these printing templates were called boilerplates
- That's where 'boilerplate' comes from

```
<!-- identifies the version of HTML we're using, which is HTML5. Browser will render our HTML file using HTML5 code -->

<!DOCTYPE html>
```

```
<!-- Tells browser that everything in between the opening and closing tags is going to be HTML code -->

<html>
</html>
```

```
<!-- head is part of the HTML that holds information about our webpage. Think of it as like a label -->

    <head>
    </head>
```

```
<!-- meta element is called character set. This gives additional info about our website. Telling the browser that all the text in our webpage is encoded using the utf-8 encoding system -->

    <meta charset="utf-8">
    <title>Grace's Personal Site</title>
```
- See www.fileformat.info/info/charset/UTF-8/list.htm
- Sometimes when you open up a webpage on an older version of a browser (like Internet Explorer) or open an up a website from Bulgaria, you'll see strange characters on the page
    - This is called mojibake, which is the Japanese word for "characters that are transformed"
    - This occurs because our browser is trying to render the characters using the wrong character set (or set of characters)
    - In short, if we're using common characters, like from the English language, and not a language like Arabic, then set the meta charset to equal "utf-8"
- "utf-8" is a character set that includes international languages
- See W3 Schools to see other attributes we can use in our meta element. Search `html <meta> tag w3 schools`
    - Give information on how search engines should display information on search results pages
    - Right-click on any page and select "View Page Source"
        - We'll then see all the source code, or all the hard work, that went into creating that webpage
        - On MDN site's source code, CTRL + F to find "description". See the value of this description within the meta tag
        - Then do a Google search. You'll notice that the description appears in Google's search results page for "mdn"
        - So browser will "crawl" through your code, and see the value of the description attribute within the meta tag