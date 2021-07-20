# loops

**Q:** Javascript has many kinds of `for loops`, how do you make use of them?

> The most common kind of `for` loops are: `for`, `for/in`,`for/of`. And every kind has some advantages over others. To use them efficiently, we need to know how they work. When we need to use a loop, we should ask ourselves some questions: which data structure are we going to loop through?, or do we know how many iterations are necessary? Are we going to access array indexes? 
By answering these guiding questions, we will be able to use the right iteration tool available. For the first question, knowing that we have an array will allow us eliminate the use of `for in` loop. Also, knowing we have an object will help us eliminate the use of `for of`. If we can know how many iterations are needed, `for loop` may be the best option or in case we don't know and it depends on some conditions, `while loops` may be the best option. Lastly, when we will need to access array using indexes, or skip some indexed positions in the array, `for loop` may be the best loop as `for of` works only with element in the array.
**Note:** `for in` loop will work with arrays but it will use indexes as keys. In case we need to have those indexes, we may use it but the down side is the correct order is not guaranteed because objects do not have a specific order.
---
**Q:** Javascript has two kinds of `while loops`, how do you make use of them?

> Javascript has two `while loop`: `while` and `do...while`. `do...while` is a variant of `while` loop as they work very similarly. Depending on the situation, we may prefer one over the other. We need to know how they work: `while` has its `condition` check at the beginning whereas `do ...while` has its condition at the end. So a block of code using `while` may not execute even once but on the other hand a block with `do...while` will execute at least once. That behavior will help us decide which one fits our need depending on the given situation.Their syntaxes are:
```javascript
\\while loop
while (condition){
    statement
}
\\do... while
do {
    statement
} while(condition);
``` 
**Note:** It is very important to initialize and increment/decrement variables correctly to avoid infinite loops.

**Q:** What are javascript methods that could replace for loop?

> Depending on the algorithm we have developped, we can make use of array methods to replace loop, they are called `array iteration methods`. Some of them are:
* `.forEach()` array method which uses a callback function on every element in the array. This method can take three (3) arguments but if the callback function does'nt need all of them, we can provide just the needed arguments.
* `.map()` works very similarly, use a callback function on every item in the array and return a new array. The returned array will have the same length. 
* `.filter()` makes use of a callback function and create a new array with array elements that passed a test.
* `.reduce` runs a function on each array element to reduce it to a single value. (It can accept an initial value)
* `.reduceRight()` same as the `.reduce` but starts on the right side.
* `.every()` checks if all array values pass a test. A boolean will be return.
* `.some()` checks if some array values pass a test.
* `.indexOf()` searches for an array for an element value and returns its position. It doesn't need a callback function.
Besides `.indexOf()`, all of the above methods work in the same logic and have the same syntax. As example:
with `.forEach`:   
 `Array.forEach(callbackfunction)`.   
But `indexOf` has a different syntax:   
`Array.indexOf(item(required), start)`   
Knowing how to use available methods can make our code very short and at the same time make us more efficient.
