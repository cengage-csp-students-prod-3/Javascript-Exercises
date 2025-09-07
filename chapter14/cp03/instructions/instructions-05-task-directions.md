## Task 05

Add the following methods to the `cart` and `foodItem` prototypes:

- Add `calcItemCost()` to `foodItem` prototype. Have the method return the product of the `price` property multiplied by the `qty` property.

> Hint: Use the `this` keyword to reference the `foodItem` object.

- Add `calcCartTotal()` to the `cart` prototype. Have the method, which calculates the `cartTotal` (the total cost of all items ordered), loop through the contents of the items array and apply the `calcItemCost()` method to each item in the array. Store the sum of the item costs in the `totalCost` property and return that value.

- Add `addToCart()` to the `foodItem` prototype. The method has a single parameter named `cart` representing the shopping cart to which the item should be added. Use the `push()` Array method to add the `foodItem` object to the `items` array of the cart.

> Hint: Use the this keyword to reference the `foodItem` object.

- Add `removeFromCart()` to the `foodItem` prototype. The method has a single parameter named `cart` representing the shopping cart from which the item should be removed. Loop through the items array in the cart object and for each item test whether it is equal to the `foodItem` object. If it is, use the `splice()` method to remove the object from the items array and break off the for loop.

> Hint: Use the `this` keyword to reference the `foodItem` object and use the `splice(index, 1)` to remove the `foodItem` where index is the counter variable in the for loop.
