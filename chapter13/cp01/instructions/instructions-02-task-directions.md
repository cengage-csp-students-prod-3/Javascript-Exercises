## Task 02

Return to the _mp_links.js_ file in your editor and create an event listener for the load event that runs an anonymous function.

Within the anonymous function, create the `allSelect` variable referencing all `select` elements nested within the "govLinks" `form`.

Loop through the `allSelect` object collection and for each selection list in the collection create an anonymous function for the `onchange` event. Within this anonymous function, use the `href` property of the `location` object to change the page shown in the browser window to the value of the target of the event object that initiated the `onchange` event.
