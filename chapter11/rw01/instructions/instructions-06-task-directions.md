## Task 06

Create the `findErrors()` function that will highlight incorrect cells by displaying the cell number of an incorrect cell in a red font. Add the following commands:

- Create a `for` loop that goes through all of the cells in the `allCells` object collection. If the cell belongs to the `blocks` class but has a background color of rgb(101, 101, 100) or if it belongs to the `circles` class but has a black background, change the font color to **red**.

- The red font colors should appear only briefly. After the for loop, insert a `setTimeout()` method with a 1-second interval. Within the `setTimeout()` method, add an anonymous function that loops through every cell in the `allCells` collection, changing all cells with a font color of red back to white.
