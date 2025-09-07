Open the _cc_data.js_ file and study the data stored in the staff object to become familiar with its contents and structure.

Go to the _cc_staff.js_ file in your editor. Richard has already created a constructor function for the class of `employee` objects storing each employee’s `id`, `firstName`, `lastName`, `dept`, `position`, `email`, `phone`, and `photo`. He has also already created an object literal named `searchResult` that will be used to store the search results in an employees array.

## Task 02

Go to the event listener for the click event. This event listener will run the code that displays the search results in a staff table. Within this event listener, add the code for Task 3 through Task 9.

Richard has added the `removeChildren()` method to the prototype of the `HTMLElement` object that removes all children from a DOM element. Apply this method to the `tableBody` variable to remove all table rows that might still be present in the staff table from previous searches.
