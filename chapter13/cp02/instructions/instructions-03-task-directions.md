## Task 03

Create the `calcClass()` function with a single parameter sumClass. The purpose of this function is to sum the values of input elements belonging to the sumClass class of elements. Add the following commands to the function:

- Create a variable named `sumFields` containing the object collection of all elements belonging to the `sumClass` class.

- Create a variable named `sumTotal` that will be used to keep a running total of the total values in the input elements in the `sumFields` object collection. Set the initial value of `sumTotal` to **0**.

- Loop through the items in the `sumFields` object collection. For each item, declare a variable named `itemValue` equal to the numeric value of the current input element in the `sumFields` array. If `itemValue` is a numeric value, add it to `itemValue`.

> Hint: Use the `parseFloat()` function to extract the numeric value.

> Hint: Use the `isNaN()` function to determine whether `itemValue` is or is not a number.

After the for loop, return the value of `sumTotal`.
