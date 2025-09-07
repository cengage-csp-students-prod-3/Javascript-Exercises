## Task 09

Create the `switchTypeDirection()` function to toggle the typing direction between right and down.
Add the following commands to the function:

- Declare the variable `typeImage` that points to the element with the ID “directionImg”.

- Create an `if-else` structure that tests the value of the `typeDirection` global variable.

- If `typeDirection = “right”`, then change `typeDirection` to **“down”**, change the `src` attribute of `typeImage` to _"pc_right.png"_, and change the background color of `currentLetter` to the red color value **rgb(255, 191, 191)**; otherwise change the `typeDirection` to **“right**”, change the `src` attribute of `typeImage` to _“pc_down.png”_, and change the background color of current letter to **rgb(191, 191, 255)**.
