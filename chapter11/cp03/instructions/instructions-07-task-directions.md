## Task 07

Create the `selectLetter()` function. The purpose of this function is to allow users to select puzzle cells using the keyboard. Add the following commands to the function:

- Declare the `leftLetter`, `upLetter`, `rightLetter`, and `downLetter` variables and set their values to reference the letters to the left, above, to the right, and below the current letter selected in the table. (_Hint_: use the `dataset.left, dataset.up`, `dataset.right`, and `dataset.down` properties of `currentLetter`.)
- Store the code of the key pressed by the user in the `userKey` variable. (_Hint_: use the `keyCode` property of the event object to retrieve the key code value.)
- Add the following `if-else` structure to determine the program response based on the value of `userKey`:
  - If `userKey` equals **37** (the left arrow key), call the` formatPuzzle()` function using `leftLetter` as the parameter value
  - If `userKey` equals **38** (the up arrow key), call `formatPuzzle(`) with the `upLetter` variable.
  - If `userKey` equals **39** or **9** (the right arrow and tab keys), call `formatPuzzle()` with the `rightLetter` variable.
  - If `userKey` equals **40** or **13** (the down arrow and enter keys), call `formatPuzzle()` with the `downLetter` variable.
  - If `userKey` equals **8** or **46** (the backspace or delete keys), delete the text content of `currentLetter`.
  - If `userKey` equals **32** (the spacebar key), run the `switchTypeDirection()` function to change the typing direction.
  - If `userKey` is between **65** and **90** (the letters a through z), write the character into the cell by changing the text content of `currentLetter` to the value returned by the `getChar()` function using `userKey` as the parameter value and then move to the next cell in the puzzle. If `typeDirection` is **“right”**, move to the next cell by calling the `formatPuzzle()` function with the `rightLetter` variable; otherwise, go down to the next cell by calling the `formatPuzzle()` variable with the `downLetter` variable.
- After the `if-else` structure, enter a command to prevent the browser from performing the default action in response to the keyboard event.
