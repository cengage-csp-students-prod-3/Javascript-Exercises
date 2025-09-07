## Task 06

Next, populate the figure box with preview images of the five fancy style sheets. Insert a `for` loop with an index that goes from **0** up through **4** and each time through the loop do the following:

1. Create an `img` element node named `sheetImg` with a `src` attribute of “**na_small_num.png**” and an `alt` attribute value of “**na_style_num.css**” where **num** is the value of the index in the `for` loop.
2. Have the browser load a different style sheet when the user clicks one of the thumbnail images by adding an event handler to `sheetImg` that runs an anonymous function changing the `href` attribute of the link element with the ID “fancySheet” to the value of the `alt` attribute of the event target.
3. Append sheetImg to the `figBox` element node.
