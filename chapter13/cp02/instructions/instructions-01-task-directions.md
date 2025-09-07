Use your editor to open the _dl_expense_txt.html_ and _dl_expense_txt.js_ files. Enter **your name** and **the date** in the comment section of each file, and rename them as _dl_expense.html_ and _dl_expense.js_ respectively.

Take some time to study the class names for the input elements in the `travelExp` table. This table will be used to calculate the total travel expenses for each day and across all categories. Note that input elements that contribute to the total are placed in the `sum` class. Input elements belonging to a common date are placed in the `date0` through `date5` classes. Finally, input elements belonging to different expense categories are placed in the `trans`, `lodge`, `meal`, and `other` classes.

## Task 01

Return to the _dl_expense.js_ file in your editor. Directly below the initial comment section, add an event listener for the load event. Apply an anonymous function to the load event that does the following:

Declares a variable named `changingCells` that matches all input elements in the `travelExp` table that belong to the `sum` class.

For every item in the `changingCells` collection, adds an `onchange` event handler that runs `calcExp()` function.

For the button with the ID “submitButton”, adds an event handler for the click event that runs the `validateSummary()` function when the button is clicked.
