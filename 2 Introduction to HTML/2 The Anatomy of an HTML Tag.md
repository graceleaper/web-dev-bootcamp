# The Anatomy of an HTML Tag

```
<h1>Hello World!</h1>
```

- `<h1>` is a start (or opening) tag
- `</h1>` is a end (or closing) tag
- `h1` is the name of the element, which is a level 1 heading
- We have content between the opening and closing tags
- Publisher will make a squiggly line under the word they want bolded
- In our case, the "publisher" happens to be our browser

```
<br>
```
- The line break is an example of a self-closing tag
- How do we know if something is self-closing or requires a closing tag?
- Head to documentation
- devdocs.io
    - See note on "Tag omission"

```
<hr>
```
- Add two horizonal lines (one above book title, and the other below author name)
- Notice that the horizonal lines we generated are thinner than the ones from _The Sherlock Holmes_ HTML copy
- "Inspect" on one of the horizonal lines on the HTML copy of the book
- We see there is a "size" and "noshade" attribute
- See devdocs.io on the attributes for an `<hr>`
- *** Attributes are properties we can change on an HTML element, so we're not restricted to displaying the default look of an HTML element
    - An attribute comes after the element name, separated by a single space. The "value" of an attribute is enclosed in quotes

- Comments
    - Making comments/notes to yourself and for others to read (but don't want to show up on the browser):
    ```
    <!-- Use to create an extra space between content -->
    <br>
    ```

    - Can make multi-line comments by placing the closing ashes and angle bracket on a separate line
    - Goldmine of a resource to jog your memory on all the lessons that you learned