## Task 12

Finally, add a table row to the body of the staff table: one row for each employee record. Apply the `forEach()` method to `employees` array in the `searchResult` object and for each record in the array, append the following document fragment to the `tableBody` object

```
<tr>
  <td><img src="photo" /></td>
  <td>first last</td>
  <td>dept</td>
  <td>position</td>
  <td><a href="mailto:email">email</a></td>
  <td><a href="tel:phone">phone</a></td>
</tr>
```

where `photo` , `first` , `last` , `dept` , `position` , `email`, and `phone` are the values of the `photo`, `firstName`, `lastName`, `dept`, `position`, `email`, and `phone` property of the current record in the `employees` array of the `searchResult` object.
