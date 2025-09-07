## Task 02

Create the `findKeyWords()` function to locate the keywords from the document and generate the keyword list. Within the `findKeyWords()` function, do the following:

Create an `aside` element with the ID “keywords” and containing an `h1` heading with the text “Keyword List”.

Create an `ol` element and append it to the keywords `aside` element.

Next, generate the list of keywords and add IDs to each keyword entry in the source article. Create an object collection named `keyWordElems` referencing all `dfn` elements within the `doc` article

> Hint: Use the `querySelectorAll()` method.

Create an array named `keyWords` with a length equal to the length of the `keyWordElems` collection. Add a `for` loop that loops through all the items in the `keyWordElems` object collection, and `for` each item do the following:

- Set the value of each item in the `keyWords` array to the text of the corresponding item in the `keyWordElems` object collection.

- Next, set the ID of the current item in the `keyWords` array. However, the ID cannot contain blank spaces. Norene has supplied you with the `replaceWS()` function to replace blank spaces with the “\_” character. Call the `replaceWS()` function with the current keyword as the parameter value and store the value returned by the function in the `linkID` variable.

- Set the ID of current item in the `keyWordElems` object collection to “keyword_linkID” where linkID is the value of the `linkID` variable.

Sort the `keyWords` array in alphabetical order.

Next, generate the list items in the keyword list. Add a `for` loop that loops through each item in the `keyWords` array, doing the following for each item:

- Declare the `keyWordListItem` variable, storing an `li` element.

- Declare the `keyWordLink` variable storing an `a` element.

- Change the `innerHTML` of `keyWordLink` to the value of the text of the current keyword.

- Declare the `linkID` variable containing the value returned by the `replaceWS()` function using the current keyword as the parameter value.

- Change the `href` attribute of `keyWordLink` to “#keyword_linkID” where linkID is the value of the `linkID` variable.

- Append `keyWordLink` to `keyWordList` and then append `keyWordList` to the ordered list you appended to the `aside` element in the "Keyword List".

Insert the keywords list box you defined as the first child of the `article` element with the ID “doc”.
