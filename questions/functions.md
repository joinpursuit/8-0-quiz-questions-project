# **FUNCTIONS**

<br>
<br>

## **Q. How do you define a function?**

> **A.** You can define a function using the keyword `function` followed by the function `name` and parameters `()` and the function body `{}`

example:
```js
//function returns `Hello World!` when called
 function name() {
     return 'Hello World!'
 }

```
<br>
<br>

## **Q. How do we call a function?**

> **A.** We can call a function by using the function `name` followed by the parameters `()`

example:
```js
//calls the `name()` function
 name()
```
<br>
<br>

## **Q. Why do we use functions?**

> **A.** We can use functions to organize reusable blocks of code.

example:
```js
//Multiply `numbers` smaller than 10 by 2 and divide `numbers` greater than 10 by 2
function greatOrLessTen(number){
    if( number < 10){
       return multiply(number);
    }else {
       return divide(number);
    }
}

function multiply(number) {
    return number * 2;
}

function divide(number) {
    return number/2;
}

console.log(greatOrLessTen(5));
//output: 10

```
