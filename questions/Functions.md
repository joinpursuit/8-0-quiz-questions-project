# Functions Questions....

<p>&nbsp;</p>

## Q: 1. How do you define a functions?   
```js
1 function functionName() {}

``` 
> **Answer:** A JavaScript ```function ```is defined with the function keyword, followed by a name, followed by parentheses ().

<p>&nbsp;</p>


## Q: 2. What is the length of the function example below named: “foo”?  


```js

1 function foo(a,b,c){
2    return 10;
3 }

```
> **Answer:** 3 -- The length property indicates the number of parameters expected by the function

<p>&nbsp;</p>
<p>&nbsp;</p>

## Q: 3. In a function, what does the word “arguments” refer to?  
```js
1 x = sumAll(1, 123, 500, 115, 44, 88);
2 
3 function sumAll() {
4  let sum = 0;
5  for (let i = 0; i < arguments.length; i++) {
6    sum += arguments[i];
7  }
8  return sum;
9 }

//Output: JavaScript Functions
//        Sum of all arguments:
//        871

```   
> **Answer:** It is a property of the function, and is an array-like list of the arguments that were actually passed into the function
