## Task 04

Create the `buttonClick()` function. The purpose of this function is to change what appears in the calculator window when the user clicks the calculator buttons. Add the following commands to the function:

- Declare the `calcValue` variable equal to the value attribute of the `calcWindow` text area box.

- Declare the `calcDecimal` variable equal to the value attribute of the decimals input box.

- Each calculator button has a `value` attribute that defines what should be done with that button.  
   Declare the `buttonValue` attribute equal to the `value` attribute of the event object target.

- Create a `switch-case` structure for the following possible values of the `buttonValue` variable:

  - For “del”, delete the contents of the calculate window by changing `calcValue` to an empty text string.
  - For “bksp”, erase the last character in the calculator window by changing `calcValue` to the value returned by the `eraseChar()` function using `calcValue` as the parameter value.
  - For “enter”, calculate the value of the current expression by changing `calcValue` to:

    ```
    “ = “ + evalEq(calcValue, calcDecimal) + “\n”
    ```

    > Note that `\n` is used to add a line return at the end of the answer.

  - For "prev", copy the last equation in the calculator window by changing `calcValue` to the value returned by the `lastEq()` function using `calcValue` as the parameter value.

  - Otherwise, append the calculator button character to the calculator window by letting `calcValue` equal `calcValue` plus `buttonValue`.

- After the `switch-case` structure, set the `value` attribute of the `calcWindow` text area box to `calcValue`.
- Run the command `document.getElementById(“calcWindow”).focus()` to put the cursor focus within the calculator window.

Next, you will control the keyboard actions within the calculator window. Theresa wants you to program the actions that will happen when the user presses the **Delete**, **Enter**, and **up-arrow keys**.  
Add the `calcKeys()` function containing the following commands:

- As you did in the `buttonClick()` function, declare the `calcValue` and `calcDecimal` variables.
- Create a `switch-case` structure for different values of the key attribute of the event object as follows:

  - For “Delete”, erase the contents of the calculator window by changing `calcValue` to an empty text string.
  - For “Enter”, add the following expression to `calcValue`:

    ```
    “ = “ + evalEq(calcValue, calcDecimal)
    ```

  - For “ArrowUp”, add the following expression to `calcValue`:

    ```
    lastEq(calcWindow.value)
    ```

  - And then enter a command that prevents the browser from performing the default action in response to the user pressing the **up-arrow key**.

- After the `switch-case` structure, set the `value` attribute of the `calcWindow` text area box to `calcValue`.
