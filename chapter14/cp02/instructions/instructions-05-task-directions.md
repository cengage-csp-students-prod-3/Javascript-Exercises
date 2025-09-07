## Task 05

Create a `switch-case` structure for the following possible values of the `nameSearchType` variable:

- If `nameSearchType` equals “contains”, use the new `RegExp()` constructor to create a regular expression object named `nameRegExp` containing the regular expression `nameSearch` where`nameSearch` is the value of the `nameSearch` variable. Include the “i” flag with the regular expression object so that the regular expression matches lowercase or uppercase characters.

- If `nameSearchType` equals “beginsWith”, set `nameRegExp` object to the regular expression `^nameSearch`, once again with the “i” flag.

- If `nameSearchType` equals “exact”, set `nameRegExp` object to the regular expression `^nameSearch$` with the “i” flag to allow for uppercase and lowercase matches.
