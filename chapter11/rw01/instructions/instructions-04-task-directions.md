## Task 04

Add the `switchPuzzle()` function, which switches the page between the three possible Hitori puzzles. Include the event object e as a parameter of the function and add the following commands:

- Declare the `puzzleID` variable equal to the ID of the event object target.

- Change the inner HTML of the element with the ID “puzzleTitle” to the value of the value attribute of the event object target.

- Create a `switch-case` structure with the `puzzleID` variable that loads the appropriate HTML code for each of the three puzzles into the page element with the ID “puzzle”. Use the `drawHitori()` function to generate the HTML code and assume that `puzzleID` is limited to the values “puzzle1”, “puzzle2”, and “puzzle3”.

- After the `switch-case` structure, call the `setupPuzzle()` function to set up the features of the selected puzzle.

- Enclose all of the commands in the `switchPuzzle()` function within an if statement that ­displays a confirm dialog box asking users whether they want to switch puzzles even though their work will be lost. If the confirm dialog box returns a value of true, run the commands within the if statement command block.
