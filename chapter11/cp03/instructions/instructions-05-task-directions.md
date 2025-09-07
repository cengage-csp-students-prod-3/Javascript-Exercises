## Task 05

Next, create the `formatPuzzle()` function. This function will format the colors of the crossword table cells and the clues in the clues list based on the letter that is selected by user. The function has a single parameter named `puzzleLetter`. Add the following commands to the function:

- Change the value of `currentLetter` to `puzzleLetter`.
- Remove the current colors in the puzzle by looping through all items in the `allLetters` object collection, changing the background-color style of each to an empty text string.
- After the `for` loop, remove the highlighting of the current clues by changing the color style of `acrossClue` and `downClue` to an empty text string.
- Determine whether there exists an across clue for the current letter by testing whether `currentLetter.dataset.clueA` is **not equal** to `undefined`. If true, then do the following:
  - Set `acrossClue` to reference the element with the `ID` value of `currentLetter.dataset.clueA` in order to reference the across clue for the current letter.
  - Change the **color** style of `acrossClue` to **blue**.
  - Set `wordLetters` to reference all elements selected by the CSS selector `[data-clue-A =clue]` where `clue` is the value of `data-clue-a` for `currentLetter`.
  - Change the `background-color` style of every item in `wordLetters` to the light blue color value **rgb(231, 231, 255)**.
- Repeat _Step 4_ for the down clue indicated by the `data-clue-d` attribute, changing the **color** style of `downClue` to **red** and the `background-color` style of the items in `wordLetters` to the light red color value **rgb(255, 231, 231)**.
- Indicate the typing direction for the current letter. If `typeDirection = “right”`, change the background color of `currentLetter` to the blue color value **rgb(191, 191, 255)**; otherwise, change the background color to the red color value **rgb(255, 191, 191)**.
