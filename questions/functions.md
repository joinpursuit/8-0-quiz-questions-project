# Functions

**Q:** What error will occur if you try to run the following code? And why?

```js
function errorExpected(){
    let x = 'will this print?'
}
console.log(x)
```

> You will get a `ReferenceError`. This is because x is defined inside the function and we are trying to call on it outside of the fucntion. It is a scope issue. 

---

**Q:** What will be printed to the console in the following code and why?

```js
function whatWillConsole(){
    let x = 'hello '
    let y = 'world'
    let z = '!'
    console.log(x + y + z)
}
```

> Nothing will console since the function was not called. The `console.log(x + y + z)` that you see would occur only in the function `whatWillConsole` is called.

---

**Q:** How many parameters does the following function have and what are they?

```js
function howManyParameters(here, there, everywhere){
    let everywhere = here + there
}
```

> There are three parameters and they are `here`, `there`, and `everywhere`.

---

**Q:** What is the purpose of functions?

> Functions act as a way to store an action that you need multiple times in your code. You can pass different arguments through your function throughout you code to see how they pass through the actions you gave to the fucntion. 
---