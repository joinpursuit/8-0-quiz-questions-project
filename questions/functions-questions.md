# Functions

**Q:** What is the difference between `console.log` and `return` when used within functions?

> **Answer**:

>`console.log` can be used within a function and outside a function. In both instances, whatever that is passed within its parameter will output onto the console.

> `return` can only be used within a function body. Using one outside a function will output an error: `SyntaxError: Illegal return statement` When used appropriately, nothing will be outputted to the console. `return` is the result (what we get back) after we've called the function. If there is no return statement, the function will return `undefined`. Once something is returned from a function, the function has ended.

---

**Q:** What does the following code print to the console?

```js
function pursuitCore() {
  return pursuitFellow;
  pursuitFellow = "awesome people";
}

console.log(pursuitCore());
```

> **Answer**:

> `ReferenceError`. This is because the pursuitFellow variable cannot be returned before it's defined. Within a function, JavaScript reads from top to bottom inside a function.

---

**Q:** What is the difference between an argument and a parameter, as indicated in the function below?

```js
function nameOfFunction (parameter) {
  function body;
}

nameOfFunction(argument);
```

> **Answer**:

> A `parameter` is a named variable passed into a function. These are found within the parentheses after the function name.

> An `argument` is a value that is passed as input to a function. These are found within the parentheses after the function name when the function is called or outside of the declared function.

---

**Q:** What does the following code print to the console?

```js
function multipy(a, b) {
  return a * b;
}

console.log(multipy(1, 2, 3, 4));
```


> **Answer**:

> `2` 

>When there are more arguments into the function than parameters declared, they are simply ignored. So in this case, `1` and `2` are multipied by the function, while `3` and `4` are ignored.  

---