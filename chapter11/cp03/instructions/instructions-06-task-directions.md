## Task 06

Return to the `init()` function and add the following commands to apply the `formatPuzzle()` function:

- Color the crossword puzzle’s first letter by calling the `formatPuzzle()` function using `currentLetter` as the parameter value.
- Users should be able to select a puzzle cell using their mouse. Loop through the items in the `allLetters` object collection and for each item:
  - Change the cursor style to pointer.
  - Add `onmousedown` event handler that runs an anonymous function calling the `formatPuzzle()` function using the event object target as the parameter value.
