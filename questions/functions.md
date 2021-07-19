# Example

**Q-1:** What is a `return` statement used for?

> A-1: A `return` statement that indicates that the function will stop executing. If the return statement is used in the function body, the execution of the function is stopped. The function will immediately stop at the point where `return` is called.

---

**Q-2:** How is a JavaScript `function` defined, and why would you want to create one?

> A-2: A `function` is a block of code that performs a specific task. It contains code that you might want to use more than once in your code to re-use it, or to call the code at a later time. This saves time from having to type out the code over and over (repeating ourselves), and also makes the entire file take up less lines and easier to read.

---

**Q-3:** What are `parameters` and `arguments`, and how do these work in the function below?

```js
function learnFunctions (param1, param2) {
    console.log("How will this function be called, and what will it return when called?");
    return param1 + param2;
}
learnFunctions(5, 6);
```

> A-3: Function `parameters` are found inside the parentheses () of the function definition.  Function `arguments` are the values that are passed in to the function when it's invoked.

> The `parameters` in this function are `param1` and `param2`. After the console.log is printed to the console, the return statement runs. This is returning `param1` + `param2` but the values are not indicated in the `parameters` themselves. The values are stored as `arguments` when the function is called. The values of the arguments being passed into the function in this case are `5` and `6`. The function will return `11` to the console.

---
