# Lists and Tables

We can create lists in HTML. The most common example is the *unordered-list*, which by default creates a list of bullet points. 

The unordered-list is represented by `<ul>`, and each *list-item* is represented by an `<li>` tag, as so:

    <ul>
      <li>foo</li>
      <li>bar</li>
      <li>baz</li>
    </ul>

We can also create *tables*. Each table generally is composed of a table-head (`<thead>`) and a table-body (`<tbody>`).

The table-head is composed of table-rows (`<tr>`), each of which is composed of table-headers (`<th>`).

The table-body is also composed of table-rows (`<tr>`), each of which is composed of table-data cells (`<td>`).

A table with a column for 'Name' and a column for 'Age' might look like this (try it yourself).

    <table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Joe</td>
            <td>30</td>
        </tr>
        <tr>
            <td>Beth</td>
            <td>30</td>
        </tr>
    </tbody>
    </table>

This table clearly lacks styles - some borders on the cells, at least. We'll get to that. 

## Exercises

1. Make a list of numbers (one, two, three). 
2. Give that list a yellow background.
3. Give each item in the list a red border.
4. Create a multiplication table with 2 columns (numbers 1, 2) and 2 rows (numbers 3, 4), with each cell showin the result of the column times the row. 
5. Give each cell have a background color of purple. 

Solution: https://jsfiddle.net/sellarafaeli/zc7foyq8/