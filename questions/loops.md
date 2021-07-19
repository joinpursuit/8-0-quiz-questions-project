# Loops!

## What is a loop?

- A loop repeats a block of code a certain amount of times or until it meets a certain condition. Javascript uses different loops in order to perform different tasks. Javascript uses for, for in, for of, while, and do while loops.

EXAMPLE:
```js
for (let i = 0; i < arrayExample.length; i++)
```
- The above example displays a for loop. The variable “i” is representing the index of the array: arrayExample. Since Javascript starts its array count at 0, the first element of the array is classified as 0. This means that we want to start the loop from the first index of the array. We use comparison operators (i.e. >, <) in order to meet a condition. The .length property is used in order to return the number of elements inside of the array. Therefore, the index is going to loop through the number of elements inside of the array. In the last part of the loop, we are using operators (++) to add one to the index. The loop will start at the first index (0) and then add one to the index as long as the index is less than the number of elements in the array.

## What is an advantage of using a for loop versus a for-of loop?

- The advantage of using a for loop over a for-of loop is that it stops the loop if a certain condition is met.

### If we are using a while loop, the condition continues to be true and we DO NOT increase the value of our number, what will be the outcome of our loop if it continues to run?

- An infinite loop will be created, this will cause the computer to run out of memory, freeze and/or cause an error message. This happens because the loop never changes, the condition continues to be true and so it never needs to come to a stop. 

