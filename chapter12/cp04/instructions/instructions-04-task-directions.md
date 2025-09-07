## Task 04

Create a function named `defineDataArray()`. The purpose of this function is to populate the `tableData` array as a two-dimensional array with values taken from the rows and cells of the web table body. Add the following commands to the function:

- Declare the `tableRows` variable, which references all of the `tr` elements within the table body of the sortable table.

> Hint: Use the `querySelectorAll()` method with “table.sortable tbody tr” as the selector.

- Create a `for` loop that loops through the contents of `tableRows`. Within the `for` loop, declare a variable named `rowCells` containing the child element nodes of the current table row and declare an empty array named `rowValues` with a size equal to the length of `rowCells`.

> Hint: Use the `children()` method.

- Within the `for` loop, insert a nested `for` loop that loops through the contents of the `rowCells` variable. For each row cell, add the text content of the row cell to the `rowValues` array.

- After the nested `for` loop has finished, add the `rowValues` array to the `tableData` array.

- After the outer `for` loop has finished, the `tableData` array will contain a two-dimensional array of all of the data in the table body. Sort the `tableData` array using the `dataSort2D()` function as the compare function.
