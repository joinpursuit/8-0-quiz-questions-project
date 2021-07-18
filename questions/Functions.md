# FUNCTIONS

**Question #1**
```
Is the code in the block below a function expression or a function declaration?
```
```js
const speak = function(){
    console.log('Have a great day')
};

greet();
```
**Answer**
```
The correct answer is function expression. 

JS functions can be defined using an expression & a function expression can be stored within a variable and can be re used within our code & function declaration (function statement) defines a function with the specified parameters.
```
**Question #2**
```
How can we use the arguments inside of the function below?
```
```js
function addingTwoNums(paramOne, paramTwo) {
    let result = paramOne + paramTwo;
    return result;
}
```

**Answer**
```
In order to use the arguments inside of a function ou must declare the arguments as variables when defining the function. the first argument will be assigned to the first variable so we if run the function with two values that we pass in then both values will be added.
```
```js
addTwoNumbers(10, 20);
//> 30
```
**Question #3**
```
Based on what we know about function scope could the variables in the code block below be accessed from outside the function?
```
```js
function pursuitProject() {
    let newJourney = "success";
}
```
**Answer**
```
No. Variables declared inside a { } block cannot be accessed from outside the block.Only the variables inside of the code block of our function can be accessed and executed by the program we are running within our function.
```
