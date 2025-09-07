## Task 08 and Task 09

The starter card is added to the board by clicking a cell in the grid table where the user wants the card placed. For every image in the `cardImages` collection, create an `onclick` event handler that does the following:

- Applies the `cardImage()` method to the `myStarterCard` object to display the image of the current card in the event object target.

- Stores the row number and column number of the clicked image in the `rowNum` and `colNum` variable.

> Hint: Use the `charAt()` method to retrieve the second and third characters of the id attribute of the event object target.

- Applies the `insertCard()` method to the `squareGame.cardGrid[rowNum]` object to insert a card into the new grid. Use `myStarterCard` as the poker card and `colNum` as the location in the `insertCard()` method.

- After the card has been placed within the grid, it cannot be changed. Set the `onclick` event handler of the event target to **null** to prevent the user from re-clicking the cell later in the game.
