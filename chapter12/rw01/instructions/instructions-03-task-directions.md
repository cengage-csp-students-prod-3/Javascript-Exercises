## Task 03

Next, create the `makeKeyStyles()` function that will define the style sheet for the keywords box. Add the following commands to the function:

- Create an embedded style sheet and append it to the document `head`.

- Add the following style rules to the style sheet:

```css
aside#keywords {
  border: 3px solid rgb(101, 101, 101);
  float: right;
  margin: 20px 0px 20px 20px;
  padding: 10px;
  width: 320px;
}
aside#keywords h1 {
  font-size: 2em;
  margin: 5px;
  text-align: center;
}
aside#keywords ol {
  margin-left: 20px;
  font-size: 1.2em;
}
aside#keywords ol li {
  line-height: 1.5em;
}
aside#keywords ol li a {
  color: rgb(101, 101, 101);
  text-decoration: none;
}
```
