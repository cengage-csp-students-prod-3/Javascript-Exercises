## Task 07

Create the `columnSort()` function. The purpose of this function is to sort the web table based on the column heading that was clicked by the user. Add the following commands to the function:

- You first must determine which column was clicked by the user. Declare a variable named `columnText` equal to the text content of the event object target.

- Retrieve the index number of the column by applying the `indexOf()` method to the `dataCategories` array, using the value of `columnText` as the array value to be found. Store the index number in the `columnIndex` variable.

- If the user clicks the column heading currently used for sorting, the sorting direction is toggled between ascending and descending. If the user clicks a new column heading, the table should be sorted by the values in that column. Test whether `columnIndex` is equal to `sortIndex`. If it is, multiply the `sortDirection` variable by **-1** (to change the sort direction); otherwise set `sortIndex` equal to `columnIndex`.

- Next, you have to move the icon into the column heading cell used for sorting. First, declare the `columnNumber` variable equal to `columnIndex` plus **1**.

- Declare the `columnStyles` variable referencing the last style sheet in the document and then delete the third rule from that style sheet (the one that adds the sorting icon to the table heading cell.)

If `sortDirection = 1` (ascending), add the following style rule to `columnStyles` to display the `▲` icon

```css
table.sortable thead tr th : nth-of-type (col) : : after {
  content: ‘ \\25b2’;
}
```

otherwise, add the following style rule to display the `▼` icon for a descending sort order:

```css
table.sortable thead tr th : nth-of-type (col) : : after {
  content: ‘ \\25bc’;
}
```

where `col` is the value of the `columnNumber` variable.

- Sort the values in the `tableData` array using the `dataSort2D()` function as the compare function.

- Create and append the newly sorted table body to the web table by calling the `writeTableData()` function.
