## Task 14

Alice wants customers to be able to remove items from the shopping cart by clicking the `removeItem` button created in Task 13. Add an `onclick` event handler to `removeButton` that does the following:

- Applies the `removeFromCart()` method to `myPizza` to remove `myPizza` from `myCart`.

- Removes the `newItemRow` from `cartTableBody`.

- Changes the value of `cartTotalBox` to the value returned by the `calcCartTotal()` method applied to `myCart` (now with the removed pizza item). Displays the new total as U.S. currency.

- Displays the revised contents of `myCart` in the debugger console log.
