# Functions
**Q1:** What object woulld be used to creat a contain code that can be use later.
>A `Function` is used to store code. They are created with the `function` keyword followed by the function name, parameters in `()` parntheses, then statements in `{}` curly brackets.
```js
function funcName(parameters) {
    // statements
    return parameter * 2;
}
```
---
**Q2:** After the statments are written, How do we get the result of our code in the function.
>We use the `return` statement to specifies values in the function. If the `return` statement is in the function body, the execution of the function is stopped.
```js
function math(num1, num2) {
    return num1 * num2;
}
math(5, 3);
// Here the function will return 15.
```
---
**Q3:** How does the function differ from creating a variable?
>`Functions` allow us to creat code that performs a partcular task. When it is invoked, the code in the function will run.