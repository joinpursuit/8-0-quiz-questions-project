# Arrays and Objects!

## What is an array?

- An array allows you to store multiple values inside of a variable. An array will always contain square brackets []. However, arrays don’t always need to contain values. You can have an empty array and use different methods to add values to the array.

EXAMPLE: 
```js
const sweaterWeather = [50, 55, 60, 65]
```
- The array above displays that the variable ‘sweaterWeather’ is an array. The values inside of the array are numbers that represent the different temperatures in which it is appropriate to wear a sweater.

## What does an index mean in an array?

The index in the array is the position that the element within the variable falls in. All indexes begin at 0. Therefore, if the length of the array is 6, the index of the last element would be 5.

EXAMPLE:
```js
const array = [A, B, C, D, E, F, G]
```

The length of the array is 6; the index of A is 0, the index of B is 1, the index of C is 2...and so on.

## Which of the following is an example of an array and which is an example of an object?

```js
let clothes = ["shirt", "jeans", "skirt", “tank top”];

let clothing = {
  cute: true,
  wearable: "yes",
  name: "shirt",
};
```
As mentioned above, arrays use square brackets while objects use curly brackets. Objects also contain keys and their values. Therefore, the variable: clothes is an array and the variable clothing is an object.