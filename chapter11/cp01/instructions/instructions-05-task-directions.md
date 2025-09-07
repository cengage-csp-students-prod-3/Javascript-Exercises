## Task 05

Create the `updateCount()` function that keeps a running total of the number of characters that the user has typed into the comment text area box. Add the following commands to the function:

- Declare the `commentText` variable that references the value stored in the comment text area box.

- Use the `countCharacters()` function with `commentText` as the parameter value to calculate the number of characters in `commentText`. Store the value in the `charCount` variable.

- Declare the `wordCountBox` that references the `wordCount` input box.

- Change the value stored in the `wordCount` input box to the text string **charCount/1000** where `charCount` is the value of the charCount variable.

- If `charCount` is greater than **1000**, change the style of the `wordCount` input box to a white font on a red background, otherwise set the style to a black font on a white background.
