## Task 06

Create the `moveBubble()` method for the bubble prototype that moves the bubble across the bubble box, bouncing the bubble off the box’s wall if necessary. The method has two arguments: `height` and `width` defining the height and width of the box. Insert the following commands into the method:

- Create the following variables to define the extent of the bubble: `bubbleTop` equal to the value of the `yPos` property, `bubbleBottom` equal to the sum of the `yPos` and `radius` properties, `bubbleLeft` equal to the value of the `xPos` property, and `bubbleRight` equal to the sum of the `xPos` and `radius` properties.

- If `bubbleTop` is less than zero or `bubbleBottom` is greater than the `height` argument, then the bubble has hit the top or bottom wall; if so, change the direction of the vertical velocity by letting `this.yVelocity` equal `this.yVelocity`.

- If `bubbleLeft` is less than zero or `bubbleRight` is greater than the `width` argument, the bubble has hit the left or right wall; if so, change the direction of the horizontal velocity by letting `this.xVelocity` equal `this.xVelocity`.

- Move the bubble to its new location by adding the value of the `yVelocity` property to `yPos` and adding the value of the `xVelocity` property to `xPos`.
