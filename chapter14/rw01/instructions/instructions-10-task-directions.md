Finally, test whether the user has completed the grid table. Within the `onclick` event handler of the previous task, test whether there are more than 27 cards left in the deck. If there are more than 27 cards left, the game continues. Shift the next card from `myDeck` into the `myStarterCard` object and change the `src` attribute of `newCard` to display the image of the next starter card.

## Task 10

Otherwise, if the grid table is completed and the game is over, calculate the game score and totals for the poker hands in each row and column as follows:

- Indicate that the game is over by changing the `src` attribute of the `newCard` image to the “ag_cardback3.png” file.

- Calculate the row poker hand totals by creating a for loop with a counter variable that goes from **0** to **4**. Declare the `rowTotal` variable equal to the value returned by the `calcRowPoints()` method of `squareGame` object, using your `counter` variable as the parameter value. Add `rowTotal` to the value of the `gameTotal` property of the `squareGame` object. Display the `rowTotal` value in the element with the ID "rowindexsum" where index is the value of your `counter` variable.

- Calculate the column totals with another for loop as you did in the previous step for the row totals. Use the `calcColumnPoints()` method to calculate the totals for each column poker hand, adding the column total to the `gameTotal` property and displaying column total value in the element with the ID "colindexsum".

- Change the value of the `gameScore` input box to the value of the `gameTotal` property of the `squareGame` object.

- Show whether the user won or lost by changing the text content of the `gameResult` element to the text returned by the `squareGame` object’s `gameResult()` method.
