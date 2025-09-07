## Task 06

Go to the _co_credit.js_ file in your editor. Create an event listener for the window load event that retrieves the field values attached to the query string of the page’s URL. Add the following to the event listener’s anonymous function:

- Create the `orderData` variable that stores the query string text from the URL. Slice the `orderData` text string to remove the first `?` character, replace every occurrence of the `+` character with a blank space, and decode the URI-encoded characters.

- Split the `orderData` variable at every occurrence of a `&` or `=` character and store the substrings in the `orderFields` array variable.

- Write the following values from the `orderFields` array into the indicated fields of the order form:

  - orderFields[3] into the modelName field
  - orderFields[5] into the modelQty field
  - orderFields[7] into the orderCost field
  - orderFields[9] into the shippingType field
  - orderFields[13] into the shippingCost field
  - orderFields[15] into the subTotal field
  - orderFields[17] into the salesTax field
  - orderFields[19] into the cartTotal field
