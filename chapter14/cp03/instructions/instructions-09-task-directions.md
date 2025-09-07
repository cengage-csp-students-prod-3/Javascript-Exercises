## Task 09

Add the `addTopping()` method to the `pizza` object prototype. The method has a single parameter named “topping”. Use the `push()` Array method to add topping to the toppings array of the pizza.

Add the `calcPizzaPrice()` method to the `pizza` prototype. The purpose of this method is to calculate the total price of the pizza with all of its selected options. Add the following commands to the method:

- Based on the value of the `size` property, set the value of the pizza’s `price` property to either the value of the `size12`, `size14`, or `size16` property of the `pizzaPrice` object.

- If the pizza crust equals “stuffed” or “pan”, increase the value of the `price` property by the corresponding value of the `stuffed` or `pan` properties of the `pizzaPrice` object.

- If the `doubleSauce` or `doubleCheese` values are true, increase the `price` by the corresponding value of the `doubleSauce` or `doubleCheese` properties of the `pizzaPrice` object.

- Loop through the contents of the `toppings` array and for each topping, calculate the `qty` property of the topping multiplied by the value of the `topping` property of `pizzaPrice`. Add the value to the pizza’s price.

- Return the final calculated value of the `price` property.
