## Task 04

Create the `calcCart()` function. The purpose of this function is to calculate the registration cost and to save information about the customer’s choices in session storage. Add the following commands to the function:

- In the session storage variable `confName`, store the value “firstName lastName” where firstName and lastName are the values of the `firstName` and `lastName` fields in the "regForm" `form`.

- Store the values of the `group`, `email`, `phoneNumber`, and `banquetGuests` fields in the session storage variables: `confGroup`, `confMail`, `confPhone`, and `confBanquet`.

- The cost of the banquet is $55 per guest. Multiply the value of the `banquetGuests` field by **55** and store the result in the session storage variable `confBanquetCost`.

- Record which session the user has selected. If the selected index of the `sessionBox` selection list is not equal to **-1**, store the text of the selected option in the session storage variable `confSession` and the value of the selected option in the `confSessionCost` session storage variable; otherwise store an empty text string and the value **0** respectively.

- The user can opt to purchase a media pack for $115 containing gifts from the conference. If the user has clicked the `mediaCB` check box, store the values “**yes**” and **115** in the `confPack` and `confPackCost` session storage variables; otherwise store the values “**no**” and **0**.

- Calculate the total registration cost by storing the value

```
session + banquet + media
```

in the `confTotal` session storage variable, where session, banquet, and media are the values of the `confSessionCost`, `confBanquetCost`, and `confPackCost` session storage variables.

> Hint: Use the `parseFloat()` method to add the numeric values of the data fields.

- Call the `writeSessionValues()` function.
