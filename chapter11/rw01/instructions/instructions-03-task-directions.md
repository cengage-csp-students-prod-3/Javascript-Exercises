## Task 03

Insert a command to run the `startUp()` function when the page is loaded by the browser.

Add the `startUp()` function, which displays the contents of Puzzle 1 after the page is loaded and sets up the initial event handlers. Within the function, add the following commands:

- Change the inner HTML of the element with the ID, “puzzleTitle” to the text “Puzzle 1”.

- Call the `drawHitori()` function using the `hitori1Numbers`, `hitori1Blocks`, and `hitori1Rating` variables as parameter values and store the HTML code returned by the function in the inner HTML of the page element with the ID “puzzle”.

- Declare a variable named `puzzleButtons` referencing the page elements with the class name “puzzles”. Loop through the `puzzleButtons` object collection and for each button add an event handler that runs the `switchPuzzle()` function when the button is clicked.

- Call the `setupPuzzle()` function that defines the initial appearance of the first puzzle.

- Add an event handler to the "Check Solutions" button to run the `findErrors()` function when clicked.

- Add an event handler to the "Show Solutions" button to run the `showSolution()` function when clicked.
