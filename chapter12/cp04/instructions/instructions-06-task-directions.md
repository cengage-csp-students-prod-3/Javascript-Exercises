Load the _gi_qbs.html_ file in your browser. Verify that the table is sorted in alphabetical order by the player names (from the first column).

## Task 06

Return to the _gi_sort.js_ file in your editor. Next, you will add controls to allow the table to be sorted by any column just by clicking a column heading. Within the anonymous function for the “load” event, add a command to call the `defineColumns()` function.

Create the `defineColumns()` function. The purpose of this function is to set up the appearance and behavior of the column headings. Add the following commands to the function:

- Append a new embedded style sheet to the document `head`

- Within the new style sheet, add the following rule to display a pointer cursor over the column headings:

```css
table.sortable thead tr th {
  cursor: pointer;
}
```

- The column headings should display an icon that indicates that they are sortable. The initial content will be a blank space indicated by the character code `\\00a0`. Add the following style rule to the new style sheet:

```css
table.sortable thead tr th: : after {
  content: ‘ \\00a0 ’;
  font-family: monospace;
  margin-left: 5px;
}
```

- The first column is already sorted in ascending order. Change the icon for the first column heading to a `▲` by adding the following style rule to the new style sheet:

```css
table.sortable thead tr th: nth-of-type (1) : : after {
  content: ‘\\25b2’;
}
```

- Next, populate the `dataCategories` array so that it contains the text of all of the column headings. Create a `for` loop that loops through the th elements in the table heading. For each table heading cell, do the following:

  - Store the text content of the table heading cell in the `dataCategories` array

  - Add an event handler that calls the `columnSort()` function when the table heading cell is clicked
