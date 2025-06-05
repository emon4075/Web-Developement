# HTML Tables

## Overview
HTML tables are used to display data in rows and columns. They're perfect for presenting structured information like spreadsheets or databases.

## Code Explanation

### Table Structure
```html
<table>
    <caption>University</caption>
    <tr>
        <th colspan="2">Name & Age</th>
        <th>University</th>
    </tr>
    <tr>
        <td rowspan="3">Emon</td>
        <td>23</td>
        <td>University of Chittagong</td>
    </tr>
</table>
```

### Table Elements
- `<table>` - Container for the entire table
- `<caption>` - Table title/description
- `<tr>` - Table row
- `<th>` - Table header cell
- `<td>` - Table data cell

### Table Attributes
- `colspan="2"` - Cell spans across 2 columns
- `rowspan="3"` - Cell spans across 3 rows

### Table Styling
```css
table, th, td {
    border: 2px solid;
    border-collapse: collapse;
    width: 100%;
    text-align: center;
}

th, td {
    background-color: burlywood;
    border-radius: 10px;
    border-color: blue;
    padding: 20px;
}
```
- `border-collapse: collapse` - Removes double borders
- `padding` - Adds space inside cells
- Various styling options for appearance

## Key Points
- Tables should be used for tabular data only
- Use semantic elements (th for headers, td for data)
- Always include table headers for accessibility
- Consider responsive design for mobile devices

## Related Links
- [HTML Tables - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)
- [HTML Tables - W3Schools](https://www.w3schools.com/html/html_tables.asp)
- [Table Accessibility](https://webaim.org/techniques/tables/)