## Task 13

Next, you will complete the function that adds a pizza to the shopping cart. Go to the `addPizzaToCart()` function and insert the commands described in Task 13 through Task 15.

Declare the `myPizza` variable as an instance of the `pizza` object class. Call the `buildPizza()` function to build the ingredients of `myPizza` and then apply the `addToCart()` method to `myPizza` to add `myPizza` to `myCart`.

Items in the shopping cart are displayed in table rows of the body section of the `cartTable` table. Create the following table row structure, saved under the variable `newItemRow`

```
<tr>
  <td>summary</td>
  <td>qty</td>
  <td>price</td>
  <td>
    <input type="button" value="X" />
  </td>
</tr>
```

where "summary" is the text content of the `pizzaSummary` element, "qty" is the value of the `qty` property for `myPizza`, and "price" is the value returned by the `calcPizzaPrice()` method applied to `myPizza`.

Format price as U.S. currency using the `toLocaleString()` method described in Tutorial 13. Give the element node for the input button, the variable name `removeButton`.

Append `newItemRow` to the `cartTableBody` element.

The `cartTotalBox` input box displays the total cost of the order. Set the value of `cartTotalBox` to the value returned by the `calcCartTotal()` method applied to my cart. Format the total cost as U.S. currency.

Display the contents of `myCart` in the console log of your browser’s debugger.
