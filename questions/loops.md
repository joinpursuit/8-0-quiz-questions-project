# Loops

**Q-1:** What is a `while loop` in JavaScript?

> A-1: A `while loop` is similar to an `if statement`.  It will check if a condition is true, and will execute the code block that follows the while loop, for as long as the condition is _true_.

> A `while loop` contains a:
> * condition

```js
let num = 3;
while (num <= 5) {
    num += 1;
    console.log(num);
}
```
> Be sure to **change the value** of _num_ in the code below, or else it will infinitely log `3` to the console, because in a `while loop`, the value will _always_ be less than or equal to 5. This code will log to the console: 4, 5, 6, stopping at 6 because after that is when `num <= 5` becomes false, and the `while loop` stops.

---

**Q-2:** What is a `for loop` in JavaScript?

> A-2: A `for loop` is a condensed version of a `while loop`, but with some differences in syntax. There are 3 parts to a `for loop` which are:
* the initial value
* conditional statement - a boolean expression that checks if the loop continues.
* updates the variable after every iteration of the loop.

> Here is an example of a `for loop`:
```js
for (let num = 5; num <= 10; num += 1){
    console.log(num);
};
```

---

**Q-3:** Can you loop through an array using a `for loop`? If so, What are the steps?

> A-3: Yes! Here's how:
> * create an array to work with.
> * set the 3 parts of the for loop: initial value - set the index to a variable such as `i`; conditional statement - in this case the index is less than or equal to the length of the array using the `.length` property; update variable after every iteration of the loop, in this case it's adding +1 to the index each time.
> * print the value using `console.log `of the array with square bracket notation, using the index variable, which in this case is `i`, that loops through the array.

```js
const arr = ["hello", "world", "Pursuit"];
for (let i = 0; i <= arr.length; i += 1) {
    console.log(arr[i]);
}
```
---
