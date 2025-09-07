## Task 05

Create the `makeBranches()` function that will be used to append node branches to the node tree diagram. The function will have two parameters named `treeNode` and `nestedList`. The `treeNode` parameter stores the current node from the source article and the `nestedList` parameter stores the structure of the node tree displayed in the web page. Add the commands described in the steps below.

Each time the `makeBranches()` function is called, it is because a new node has been discovered in the source article. Increase the value of the `nodeCount` variable by **1**.

Create the following list item HTML fragment, storing the list item element in the `liElem` variable and the `span` element node in the `spanElem` variable.

```js
<li>
  +--<span></span>
</li>
```

Append the `spanElement` node to the `liElem` element node; append the `liElem` node to the `nestedList` element node.

If `treeNode` represents an element node, then do the following:

- Increase the value of the `elemCount` variable by **1**.
- Add the `class` attribute to the `spanElem` node, setting its value to “**elementNode**”.
- Append the text string “`<element>`” to the `spanElem` node, where `element` is the name of the HTML element.

> Hint: Use the `textContent` property to append the text of the element tag and not the element tag itself.

Else if `treeNode` represents a text node, do the following:

- Increase the value of the `textCount` variable by **1**.
- Declare the variable `textString` equal to the value of the text node.
- Jorge has provided a function named `isWhiteSpaceNode()` to determine whether a text node represents white space or not. Call the `isWhiteSpaceNode()` function using `textString` as the parameter value. If the function returns the value true, then do the following:
  - Increase the value of the `wsCount` variable by **1**
  - Change the `class` attribute of the `spanElem` node to “`whiteSpaceNode`\"
  - Append the text string “`#text`” to the `spanElem` node
  - If the `isWhiteSpaceNode()` function returns the value false, then do the following:
    - Change the `class` attribute of the `spanElem` node to “`textNode`”
    - Append the text string “`text`” to the `spanElem` node where text is the value of the `textString` variable.

The `makeBranches()` function should recursively move through the different levels of nodes in the source article. To apply recursion, test whether the number of child nodes of `treeNode` is greater than zero. If it is, then do the following:

- Create the following HTML fragment as an element node with the name `newList`:
  ```js
  <ol>|</ol>
  ```
- Append `newList` to the `nestedList` element node.
- Loop through the child nodes of `treeNode` using **n** to represent each child node, and for each child node to call the `makeBranches()` function using **n** and `newList` as the parameter values.
