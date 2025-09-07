## Task 03

Create the `init()` function. The purpose of the function is to define the event listeners used in the page. Add the following commands to the function:

- Declare the `stars` variable that stores an object collection of the reviewing stars, referenced by the `span#stars` img selector.
- Loop through the star collection and for each star image in the collection change the cursor style to `pointer` and add an event listener to run the `lightStars()` function in response to the `mouseenter` event occurring over each star image.
- After the `for` loop, add an event listener to the comment text area box that runs the `updateCount()` function in response to the keyup event.
