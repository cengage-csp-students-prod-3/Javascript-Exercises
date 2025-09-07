## Task 12

Go to the `buildPizza()` function that builds the pizza based on the values entered into the web form. The function has a single parameter, `newPizza`, which represents a new pizza that will be created based on the customer’s choices.

Set the `qty` property of `newPizza` to the selected value in the `pizzaQuantityBox` selection list.

> Hint: Use the `selectedValue()` method that has been added to the Array prototype to return the value of the selected option in a selected list.

Set the `size` property of `newPizza` to the selected value in the `pizzaSizeBox` selection list. Set the `crust` property of `newPizza` to the selected value in the `pizzaCrustBox` selection list.

Set the `doubleSauce` and `doubleCheese` properties of `newPizza` to the checked properties of the `doubleSauceBox` and `doubleCheeseBox` check boxes.

Declare the variable `checkedToppings`, which contains all the topping option buttons that have been checked by the user.

> Hint: Use the CSS selector `input.topping:checked` to create the object collection.

Loop through the option buttons in `checkedToppings` and for each option, test whether the option button value is not equal to “none”. If true, then do the following:

- Declare `myTopping` as an instance of the `topping` object class.

- Set the `name` property of `myTopping` to the `name` of the option button and set the `side` property of `myTopping` to the value of the option button.

- If option button value is “full”, then set the `qty` property of `myTopping` to **1**, otherwise set the value of the `qty` property to **0.5**.

- Apply the `addTopping()` method to add `myTopping` to `newPizza`.
