## Task 04

Create the `init()` function, which sets up the initial conditions of the puzzle. Add the following commands to the function:

- Set `allLetters` to reference the elements using the selector `table#crossword span`.
- Set `currentLetter` to reference the first object in `allLetters` collection
- Declare the `acrossID` variable, setting its value equal to the value of the `data- clue-a` attribute for `currentLetter`. Declare the `downID` variable, setting its value equal to the value of the `data-clue-d` attribute for `currentLetter`.
- Set the value of `acrossClue` to reference the element with the `id` attribute **\"acrossID\"**. Set the value of `downClue` to reference the element with the `id` attribute **“downID”**.
