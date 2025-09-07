## Task 04

The `makeTree()` function will be used to create the node tree for the source article on the page. Create the `makeTree()` function, adding the commands described below.

Within the `makeTree()` function create the following `aside` element fragment:

```html
<aside id="”treeBox”">
  <h1>Node Tree</h1>
</aside>
```

and append it to the section element with the ID “main”.

The node tree will be created within an ordered list. Declare a variable named `nodeList` containing the initial `ol` element node that will be the foundation of the node tree and append it to the `aside` element fragment.

The node tree will be based on the contents of the elements matching the CSS selector “`#mainarticle`”. Declare a variable named `sourceArticle` that points to these elements.

> Hint: Use the `querySelector()` method.

The contents of the node tree and the count of the different global variables will be updated using a function named `makeBranches()`, which you will create shortly. Call the `makeBranches()` function using the `sourceArticle` and `nodeList` variables as parameter values.
