# JavaScript Syntax Sandbox

This is a place to document, test & practice with JavaScript syntax.

## Rest parameters
When adding the spread operator to arguments within the function declaration, the arguments will be placed into an array.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters

```
const func = (...theArgs) => {

  // The Spread Operator will place arguments into an array

  console.log(theArgs)

  // Result:
  //[1,2,3]
}

func(1,2,3)
```
