# ☆ All About Functions! ☆ 

## What would the text inside the parenthesis be called in this function below? What does that mean?

``` js
function carParts (doors, tires, windows)
```

- Doors, tires and windows are the parameters of the function. Parameters identify what will be declared into the function. This data are the values of the arguments that will be evaluated.

## What is a return value in a function?

 ```js
 function astroWorld (sun, moon) {
     return sun * moon;
     } 
```

- The return value of the function is the product of the parameters “sun” and “moon”. The function will not continue to execute as long as that return statement is in the function.

## Given the following function, properly invoke the function and log out the return.
```js
function even (num) {
	if (num % 2 === 0) {
	return `${num} is an even number`
	} else {
	return `${num} is an odd number`
	}
} 
```
## Given the following function, properly invoke the function and log out the return.

- To invoke the function you need to use the following syntax: functionName(argument). To log the return into the console you need to you use: console.log()
In one line you can: 
```js
console.log(even(10))
Or: const functionOutput = even(10); 
      console.log(functionOutput);
```