## Task 11

Bernard wants users to be able to briefly view their mistakes. Add an `onclick` event handler to the `init()` function that runs the following commands when the user clicks the "Show Errors" button:

- Loop through all items in the `allLetters` object collection. If the text content of an item does not match the value of the letter’s `dataset.letter` property, change the color style of the letter to **red**.

- After a 3-second interval, set the `color` style for the items in the `allLetters` collection to an empty text string, restoring the letters to the default font color.
