# HTML Tables

1) Add a table to your webpage
- We don't want just a bunch of paragraphs, and have content that's not aligned. And we would also want to have some padding as well
- We can create table rows, and table data (which are like cells)
- Have two cells in a row (and refer to mdn docs on tables in HTML):

```
<table>
    <thead>
        <th>Year</th> <!-- 'table header' element-->
        <th>Milestone</th>
    </thead>

    <tbody>
    </tbody>
        <tr>
            <td>2010</td>
            <td>2018</td>
        </tr>

        <tr>
            <td>Climb Mount Everest</td>
            <td>Complete triathalon</td>
        </tr>
    <tfoot>
    </tfoot>
</table>
```

- Recap on table's boilerplate:
```
<table>
    <tr>
        <td>Grace</td>
        <td>28</td>
    </tr>

    <tr>
        <td>Samuel</td>
        <td>22</td>
    </tr>
</table>
```
- By default, our browser won't add any styling to our table. So no borders or padding
- `<tr>` will create a row
- `<td`> will create a cell
- No concept of 'columns' in HTML tables
    - So you add cells, one a time, to a row