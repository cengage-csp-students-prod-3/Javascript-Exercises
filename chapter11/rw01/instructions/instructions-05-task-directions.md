## Task 05

Create the `setupPuzzle()` function to set up the features of the puzzle table. Within the function add the following commands:

- Use the `querySelectorAll()` method to create an object collection of all of the `td` elements within the `hitoriGrid` table and save the object collection in the `allCells` variable.

- Create a `for` loop that loops the `allCells` object collection and, for each cell, change the `­background-color` style to **white**, the `font-color` to **black**, and the `border-radius` value to **0**.

- Within the for loop, add a `mousedown` event listener for each cell in the `allCells` collection that changes the cell’s appearance depending on whether the Shift key, the Alt key, or no key is pressed by the user. Add the following commands to the anonymous function for the `mousedown` event:

  - Change the `background-color` to **white**, the `font-color` to **black**, and the `border-radius` to **0** if the user is pressing the Shift key.

  - Change the `background-color` to **black**, the `font-color` to **white**, and the `border-radius` to **0** if the user is pressing the Alt key.

  - Otherwise, change the `background-color` to **rgb(101, 101, 101)**, the `font-color` to **white**, and the `border-radius` to **50%**.

  - To avoid inadvertently selecting the text of the table cells, include a command to prevent the default action of the browser in response to the `mousedown` event.

- Rebecca wants a different mouse cursor depending on whether the user is pressing the Shift key, the Alt key, or no key when the mouse pointer moves over a puzzle cell. Within the for loop, add a `mouseover` event listener for each puzzle cell that runs an anonymous function that

  - Changes the cursor to the _jpf_eraser.png_ image or the generic cursor named “alias” if the user is pressing the Shift key.

  - Changes the cursor to the _jpf_block.png_ image or the generic cursor named “cell” if the user is pressing the Alt key.

  - Otherwise, changes the cursor to the _jpf_circle.png_ image or the generic cursor named “pointer”.

- Finally, within the for loop, add an event listener that runs the `checkSolution()` function in response to the `mouseup` event to test whether the user has solved the puzzle.
