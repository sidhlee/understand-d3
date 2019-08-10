# Understand D3
## Requiring multiple d3 modules.

You can load multiple d3 modules into the project with ES6 object spread operator.
```js
const d3 = { 
  ...require("d3-array"),
  ...require("d3-queue"),
  ...require("d3-scale")
 }
 
 console.log(d3.minIndex([1, 0, 9])) // 1
 ```
