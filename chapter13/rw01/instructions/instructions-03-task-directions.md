## Task 03

Create the `calcCart()` function to calculate the cost of the customer’s order using field values in the cart form. Within the `calcCart()` function, do the following:

- Create a variable named `orderCost` that is equal to the cost of the espresso machine stored in the `modelCost` field multiplied by the quantity of machines ordered as stored in the `modelQty` field. Display the value of the `orderCost` variable in the `orderCost` field, formatted as U.S. currency.

> Hint: Use the `formatUSCurrency()` function.

- Create a variable named `shipCost` equal to the value of the selected shipping option from the group of shipping option buttons multiplied by the quantity of machines ordered. Display the value of the `shipCost` variable in the `shippingCost` field, formatted with a thousands separator and to two decimals places.

> Hint: Use the `formatNumber()` function.

- In the `subTotal` field, display the sum of `orderCost` and `shipCost` formatted with a thousands separator and to two decimal places.

- Create a variable named `salesTax` equal to 0.05 times the sum of the `orderCost` and `shipCost` variables. Display the value of the `salesTax` variable in the `salesTax` field, formatted with a thousands separator and to two decimal places.

- In the `cartTotal` field, display the sum of the `orderCost`, `shipCost`, and `salesTax` variables. Format the value as U.S. currency.

- Store the label text of the shipping option selected by the user from the shipping field in the hidden `shippingType` field.
