## Task 05

Create the `writeTableData()` function. The purpose of this function is to create the table body based on the sorted data. Add the following commands to the function:

- Create a set of nested `for` loops that builds the following node structure

```html
<tbody>
  <tr>
    <td>tableData[0][0]</td>
    <td>tableData[0][1]</td>
  </tr>
  <tr>
    <td>tableData[1][0]</td>
    <td>tableData[1][1]</td>
  </tr>
</tbody>
```

where `tableData[0][0]`, `tableData[0][1]`, `tableData[1][0]`, `tableData[1][1]`, and so on are the values from the two-dimensional tableData array. Store the node structure in a variable named `newTableBody`.`

- Use the `replaceChild()` method to replace the `tbody` element from the current web table with `newTableBody`.
