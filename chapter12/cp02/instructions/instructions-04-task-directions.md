## Task 04

Create the `addItem()` function, which adds items to the shopping cart on the page. Add the following commands to the function:

- The description of the food item is the next sibling element to the button that was clicked by the customer. Use the `nextElementSibling` property to reference the next sibling element to the target of the event object. Store the sibling element in the variable `foodItem`.

- Create the `foodID` variable, which contains the value of the `id` attribute for `foodItem`.

- Use the `cloneNode()` method to create a copy of the `foodItem` element and all of its descendants. Store this node structure in the `foodDescription` variable.

- The shopping cart is stored in an `aside` element with the ID “cart”. Store the reference to this element in a variable named `cartBox`.

- The shopping cart needs to determine whether a product ordered by the customer has already been ordered. To do this, you will add a `span` element to the top of each item in the cart containing the number of items of each product ordered and update that value when a product order is repeated. Do the following to create the order counter for each Subsistence product.

- Create a variable named `duplicateOrder` and set its initial value to **false**.

- Loop through the element child nodes of `cartBox`. For each node, determine whether the ID of the element node equals `foodID`. If it does, the customer has previously placed that menu item in the cart. Increase the value of the first element child of node by **1** to indicate an additional order and then break out of the `for` loop.

- After the `for` loop has completed, test whether `duplicateOrder` is still `false`. If it is, then create a variable named `orderCount` storing a `span` element node. Set the text content of the `orderCount` element to **1**. Insert `orderCount` as the first child of the `foodDescription` node structure and append `foodDescription` to `cartBox` as a new product order.
