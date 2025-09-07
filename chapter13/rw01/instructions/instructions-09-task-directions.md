## Task 09

Create the `validateDate()` function. The purpose of this function is to validate the credit card expiration date stored in the `expDate` field. Within the function, insert an if-else structure that tests the following:

- If no value has been entered for the expiration date, set the custom validation message to “Enter the expiration date”.

- If the expiration date does not match the regular expression pattern:

```
/^(0[1-9]|1[0-2])\ /20[12]\d$/
```

set the custom validation message to “Enter a valid expiration date”.

> Hint: Use the `test()` method.

- Otherwise set the custom validation message to an empty text string.
