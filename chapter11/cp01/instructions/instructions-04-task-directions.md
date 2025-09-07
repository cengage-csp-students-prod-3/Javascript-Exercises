## Task 04

Create the `lightStars()` function. The purpose of this function is to color a star when the user moves the mouse pointer over a star image in order to reflect the user’s rating of the book. Add the following commands to the function:

- Daniel has stored the rating value of each star image in the img element’s `alt` attribute. Store the value of the `alt` attribute of the target of the event object in the `starNumber` variable.

- Declare the `stars` variable containing the object collection referenced by the selector `span#stars` img.

- Loop through the stars collection with an index ranging from **0** up to less than the value of the `starNumber` variable. Light every star in the collection by changing the `src` attribute of the star image to the _bw_star2.png_ image file.

- After the for loop, create another loop that loops through the stars collection with the index ranging from the value of the `starNumber` variable to less than **5**. Unlight every star in this collection by changing the `src` attribute of the star image to the _bw_star.png_ image file.
- Change the value of the input box with the `id` attribute “rating” to `starNumber stars`, where `starNumber` is the value of the `starNumber` variable.

- When the mouse pointer moves off a star image, the lit stars should be unlit. Add an event listener to the target of the event object that runs the `turnOffStars()` function in response to the `mouseleave` event.

- If the user clicks the star image, the selected rating should be set, which means moving the mouse pointer off the star should not remove the rating. Add an event listener for the target of the event object that runs an anonymous function removing the `turnOffStars()` function from the `mouseleave` event.

Create the `turnOffStars()` function. The purpose of this function is to unlight the stars when the user moves the mouse pointer off the star images. Add the following commands to the function:

- Declare the `stars` variable containing the object collection referenced by the selector `span#stars` img.

- Loop through all images in the stars collection and change the `src` attribute of each image to the _bw_star.png_ file.

- Change the value of the rating input box to an empty text string.
