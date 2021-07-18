**Q:** What is function definition and declaration in JavaScript? Give an example.

```
The function declaration (function statement) defines a function with the specified parameters. You can also define functions using the function constructor and function expression.

Here is a simple example:
```
```js
//defining a function
function addUp(number1,number2) {
//Keyword function + function name + parameters in the () parenthesis + the code which will be executed inside {} opeing and closing curly squares    
}
```

**Q:** How to return a value and call a function in JavaScript? Giva an example.

```js
function addUp(number1,number2) {
    return number1 + number2; 
    // Returning the value which adds up the parameters number1 and numbers. (Code to be executed).
}
addUp(3,5); 
// Calling the function which named addUp
```

**Q:** What are the parameter rules in a function? Give an example. 

```
First, JavaScript function definitions do not specify data types for parameters.
Second, function definitions do not perform type checking on the passed arguments.
Third, function deinitions no not check the number of arguments received.

Here is a simple example:
```
```js
ffunction myFunction(x, y) {

  return y; 
}
let result = myFunction(2)
//If a function is called with missing arguments (less than declared), the missing values are set to undefined.

console.log(result) // undefined
```

