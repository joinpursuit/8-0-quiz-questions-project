# Functions

**Q1:** One way to accept arguments for a function is by using parameters within parentheses`()`. How else can functions accept arguments?

> Arguments can also be passed into a function through the use of the array `process.argv`. From the third index position onward, `process.argv` accepts arguments inputted after a function when called, when they are each separated by a space.

---

**Q2:** Consider the following code. If the array `soundEffects` is passed into `doesSomething`, what would happen?

```js
let soundEffects = ['bang', 'boom', 'pow'];

function doesSomething(){
    soundEffects[3] = 'clang';
    console.log(soundEffects);
}

doesSomething();
```
> The string 'clang' would be added to the end of the array `soundEffects`. The next available empty index is [3], which would allow 'clang' to enter without overwriting 'pow'. The function would also log the new `soundEffects` array.

---
**Q3:** Consider both the function below and the `doesSomething` function from Question 2. Are they equivalent? If not, what would make them equal?

```js
function doesSomething2(){
    soundEffects.unshift('clang');
    console.log(soundEffects);
}
```

> The two functions are not quite the same. The use of `unshift` does add the string 'clang' to `soundEffects`, but it is added in the first index position, as opposed to `doesSomething` which adds into the last position. Swapping `unshift` for `push` would provide the same result as Question 2's function.

---

**Q4:** What reason do we have for using functions? What is their strength?

> Functions are used as mini-programs within a program. They allow us to reuse a process whenever it is called with proper parameters. Variables created inside functions are also inaccessible from the outside.

