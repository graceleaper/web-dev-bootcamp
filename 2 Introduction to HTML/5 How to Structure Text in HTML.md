# How to Structure Text in HTML

1) Add a header using the `h1` element
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <h1>All About Grace</h1>
</body>
</html>
```
- Indenting our code is important. Many developers are picky about it
- Having indents will make it easy for us to see which tags are inside other ones (tags)
    - (Use markup tool to highlight?) Notice that inside html tags, we have head and body tags that are indented inside the html tags
    - Shows us at a glance where the head and body tags are
    - Notice that the head and body tags are aligned the same
    - Other programmers looking at your code will have an easier time reading through everything
    - *** Identy tags (hit 'tab' key) if the tag is inside another set of tags

2) Add a paragraph
- `<p>` tag formats text into paragraph (see W3 Schools for documentation on this)

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <h1>All About Grace</h1>
    <p>I'm a computer science teacher at The Buckley School in NYC.</p>
</body>
</html>
```
3) Italicizing and bolding words
- Notice on Jon Kleinberg's website (Cornell professor), he italicized his position
- How might we use Google to find out how to italicize words in HTML?
- Search for: 'italicize html mdn' or 'italicize html w3 schools'
- Enclose words in `<em>` tags to italicize
- Enclose words in `<strong>` tags to bold
    - We can do so for the entire sentence, or just some of the words

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <h1>All About Grace</h1>
    <p>I'm a <em>computer science teacher</em> at <strong>The Buckley School in NYC</strong>.</p>
</body>
</html>
```
4) Add a bio about yourself in a paragraph below your first paragraph

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <h1>All About Grace</h1>

    <p>I'm a <em>computer science teacher</em> at <strong>The Buckley School in NYC</strong>.</p>

    <p>I was born and raised in New York. And I love coffee.</p>
</body>
</html>
```

5) Add a horizontal line (rule)
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <h1>All About Grace</h1>

    <p>I'm a <em>computer science teacher</em> at <strong>The Buckley School in NYC</strong>.</p>

    <p>I was born and raised in New York. And I love coffee.</p>
    <hr>
</body>
</html>
```
- Our website is starting to look similar to Jon Kleinberg's

6) Add a level 3 heading underneath your horizontal line
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Grace's Personal Site</title>
</head>
<body>
    <h1>All About Grace</h1>

    <p>I'm a <em>computer science teacher</em> at <strong>The Buckley School in NYC</strong>.</p>

    <p>I was born and raised in New York. And I love coffee.</p>
    <hr>

    <h3>Education</h3>
</body>
</html>
```

- Next lesson on making lists in HTML!