# Arrays And Objects

**Q-1:** What is an `array`? Give an example.

> A-1: An `array` is a way to store multiple values. These can be any type of variables or data, such as strings and numbers. It's best to use the same data type throughout all elements in the `array`. To access an element in an `array`, the counting of the index starts at 0.
In the example below, "hello" is the first element of the `array` at index position 0. Arrays use square brackets.

```js
const arr = ["hello", "world", "Pursuit"]
```

---

**Q-2:** What is an `object` in JavaScript? Give an example.

> A-2: An `object` in JavaScript can be compared to real-world objects, such as a pen. An object is a collection of `key: value` pairs. The pairs are properties, which could be how you would describe a real-world object, such as: type, which could be 'fountain', pen color as 'green', and ink color - 'sapphire'. And you only have one pen. This is represented in an object as `key: value` pairs. To turn this real-world 'pen' object into a JavaScript object, you would write it like this (shown below), declaring it as an object using the curly brackets. This is called an `object literal`.

```js
let pen = {
    type: 'fountain';
    color: 'green';
    inkColor: 'sapphire';
    numberOfPens: 1;
}
```

---

**Q-3:** What is the built-in JavaScript method .join() that you can use on an array?

> A-3: .join() method - converts the array to a string. The string will have all the elemnts in the array, separated by a comma. Alternatively, you can pass in a separator as an _argument_. By passing in different separators as _arguments_, that will change the output of the array being logged in the console, shown below:

```js
let arr = ["hello", "world", "Pursuit"]

console.log(arr.join());  // will log: 'hello,world,Pursuit'

console.log(arr.join(''));  // will log: 'helloworldPursuit'

console.log(arr.join(' '));  // will log: 'hello world Pursuit'

console.log(arr.join('$'));  // will log: 'hello$world$Pursuit'
```
---
