# Using HTML Tables for Layout
- See www.cs.dartmouth.edu/~thc
- Notice Thomas H. Cormen's website has his photo on the left, and information about himself on the right
    - We can create this kind of layout, we can use tables

```
<table>
    <tr>
        <td><img src="image-name.png" alt="headshot"></td>
        <td>
            <h1>Name</h1>
            <p>This paragraph is all about me</p>
            <p>Another paragraph about me</p>
        </td>
    </tr>
</table>
```
- We have a table with a single row and two cells
- Notice there's a bit of a gap between the text and image for Thomas Cormen's site. We can recreate that by doing the following:

```
<!-- percentage or pixels. See mdn docs on cellspacing in tables -->

<table cellspacing="20">
    <tr>
        <td><img src="image-name.png" alt="headshot"></td>
        <td>
            <h1>Name</h1>
            <p>This paragraph is all about me</p>
            <p>Another paragraph about me</p>
        </td>
    </tr>
</table>
```
- So in the above code, we created some padding, or space, from one edge of a cell to another edge of a cell
- Challenge: Create a table where you add your skills. And use emoji stars to rate yourself on that skill
    - And add some horizontal rules to separate sections
