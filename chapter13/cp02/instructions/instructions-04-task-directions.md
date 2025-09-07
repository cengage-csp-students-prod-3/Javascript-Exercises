## Task 04

Create the `calcExp()` function. The purpose of this function is to calculate the row and column totals from the `travelExp` table. Add the following commands to the function:

- Create the `expTable` variable referencing all the table row (`tr`) elements within the table body of the `travelExp` table.

- Loop through the rows in the `expTable` collection and, for each table row, set the value of the input element with the ID `subtotalIndex` to the value returned by the `calcClass()` function using the parameter value `dateIndex`. Where `Index` is the value of the index counter in the for loop. Format the value returned by the `calcClass()` function as a text string using the `formatNumber()` function to **2** decimals.

- After the for loop, set the values of the `transTotal`, `lodgeTotal`, `mealTotal`, and `otherTotal` input elements by calling the `calcClass()` function using parameter values “trans”, “lodge”, “meal”, and “other”. Format the values using the `formatNumber()` to **2** decimal places.

- Set the value of the `expTotal` input element to the value returned by the `calcClass()` function using “sum” as the parameter value. Format the returned value using the `formatUSCurrency()` function.
