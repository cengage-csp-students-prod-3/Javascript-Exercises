## Task 07

Next, design the appearance of the thumbnail figure box. Create an embedded style sheet named `thumbStyles` and append it to the document head.

Add the following style rules to the `thumbStyles` style sheet:

```css
figure#styleThumbs {
  position: absolute;
  left: 0px;
  bottom: 0px;
}
figure#styleThumbs img {
  outline: 1px solid black;
  cursor: pointer;
  opacity: 0.75;
}
figure#styleThumbs img:hover {
  outline: 1px solid red;
  opacity: 1;
}
```
