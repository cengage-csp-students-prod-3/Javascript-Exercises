Open the _ag_squares.js_ file in your editor. Go to the `playPokerSquares()` function. Within the function add an `onclick` event handler to the `startButton` object that runs an anonymous function when the user clicks the Start Button on the web page. Within the anonymous function, do the tasks laid out in Task 4 through Task

## Task 04

Set up the initial game board by doing the following:

- Set the gameTotal property of the `squareGame` object to **0**.

- Remove the current game score by changing the value of the `gameScore` input box on the page to an empty text string.

- Remove the current game result by changing the text content of the `gameResult` element on the page to an empty text string.

- Remove the current row and column totals by looping through the contents of the `rowSumCells` and `columnSumCells` object collections, setting the text content of each cell to an empty text string.

- Remove the current card images by looping through the `cardImages` object collection, setting the source of every inline image to the “ag_trans.gif” file.
