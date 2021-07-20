> ## **What is a javascript function?**

```
A JavaScript function is a block of code designed to perform a particular task.
In other programming languages, a function is similar to a routine or subroutine.
```
> ## **What are parameters?**

```
Function parameters are the names listed in the function's definition.
Parameter variables are used to import arguments into functions.
```
> ## **Name the two kinds of arguments that are passed into a function.**

```
Primitive and object are two kinds of arguements passed as inputs to a function.
```
> ## **What is the difference between `console.log` and `return` when used within functions?** 
```
`console.log` can be used within a function and outside a function. In both instances, whatever that is passed within its parameter will output onto the console.

`return` can only be used within a function body. Using one outside a function will output an error: `SyntaxError: Illegal return statement` When used appropriately, nothing will be outputted to the console. `return` is the result (what we get back) after we've called the function. If there is no return statement, the function will return `undefined`. Once something is returned from a function, the function has ended.
```
> ## **What does the following code print to the console?**
```
function pursuitCore() {
  return pursuitFellow;
  pursuitFellow = "awesome people";
}
console.log(pursuitCore());

The answer is an `ReferenceError`. This is because the pursuitFellow variable cannot be returned before it's defined. Within a function, JavaScript reads from top to bottom inside a function.
```
> ## **What is the difference between an argument and a parameter, as indicated in the function below?**
```
function nameOfFunction (parameter) {
  function body;
}
nameOfFunction(argument);

A `parameter` is a named variable passed into a function. These are found within the parentheses after the function name.

An `argument` is a value that is passed as input to a function. These are found within the parentheses after the function name when the function is called or outside of the declared function.
```