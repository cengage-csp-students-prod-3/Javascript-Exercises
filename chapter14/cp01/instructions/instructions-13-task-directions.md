## Task 13

Otherwise, animate the bubble by adding the following the commands:

- Set the value of the `opacity` style of `bubbleImg` to the value of the `opacity` property of the `newBubble` object.

- Change the `hue` of the bubble by applying the `changeColor()` method to the `newBubble` object and applying the filter style

```
hue-rotate (huedeg)
```

to `bubbleImg` where `hue` is the value of the `newBubble`’s `hue` property.

- Spin the bubble by applying the `rotateBubble()` method to the `newBubble` object and applying the transform style

```
rotate (rotatedeg)
```

to `bubbleImg`, where `rotate` is the value of the `newBubble`’s `rotate` property.

- Move the bubble by applying the `moveBubble()` method with `box.height` and `box.width` as the argument values. Set the `top` and `left` styles of `bubbleImg` to the values of the `yPos` and `xPos` properties of the `newBubble` object.
