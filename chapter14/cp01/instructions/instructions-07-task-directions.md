Scroll down to the event listener for the load event. Drew has already inserted a `setInterval()` method that is set up to create a new bubble every half-second as long as there are no more than 20 bubbles already in the box. Drew has also nested the `randInt()` function within the event handler that returns a random integer within a specified range. You will use the `randInt()` function to create bubbles of random appearance, velocity, hue, and spin. Within the if condition, add the commands specified in following tasks.

## Task 07

Declare the `newBubble` variable using the `new bubble()` object constructor to create a `bubble`. Set the size of the bubble to a random size between 50 and 120 and the image file to “bu_bubbleint.png”, where `int` is a random integer from 1 to 10.

> Hint: Use the `randInt()` function to generate the random integers for both the `size` and `img` arguments.
