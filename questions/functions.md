# Functions

**Q:** What is a function and why is it the bread and butter of JavaScript programming? 

> **A:** Functions work like a process, a process that takes certain inputs or statements and performs a task or calculates a value. When you realize you’re typing a lot of the same things and repeating yourself, you want to use a function. For example, when you have multiple values and you want one output value, you would use a function to return one output value. So functions are a useful way to reduce repetitiveness and for scaling larger problems.  

> In Javascript, function declarations are made up of the following:
> - Function name 
> - Function can have zero or multiple parameters, which are in parentheses and separated by commas 
> - The sequence of Javascript statements that define the function, inside curly braces

```js
function name(parameter) {javascript statement}
```

> When it’s used as an expression, the _function_ keyword can be used to declare a function inside an expression.

```js
const name = function() {}
```

> In general, functions are a “subprogram,” wrapping a part of a program in a value and _calling_ it by code that’s outside the function. If you create a function, it isn’t going to print or return anything. To call the function, simply _call, run or invoke_ the function by typing the name of the `name()` and running it. So what’s also great with functions is that you can associate names with subprograms, reuse them and isolate these subprograms from one another. 

> Lastly, one interesting fact about functions is that they are a special kind of object because they can have properties and methods just like any other object. And yet, functions are different from other objects because functions can be called. So, in summary, functions are Function objects

---
---

**Q:** What are the different parts that make up the following function and how can you make it syntatically shorter?

```js 
function sayHello(name) {
  return `Hello! Nice to meet you, ${name}.`;
}
```

> **A:** Declare a `function`, which is syntactically a statement that starts with the keyword  _function_, followed by the  _function name_ `sayHello`. This function has only one  _parameter_ `name` inside a parenthesis `()`. Next, is the statement to be executed in the function body. For example, the quote `Hello! Nice to ..."` is the `return` _value_ inside the curly braces `{}`, which makes up the _function body_. Specifically, the `${name}` is known as _template literal_ or _template strings_, allowing embedded expressions. In order for this embedded expression and the entire quote to work, it is all written within single backticks (``). The embedded expression here is based on the given _parameter_ `name`.   

> **Bonus:** In order to create functions with a shorter syntax, use the arrow function expression like so:

```js
const sayHello  = (name) => {return `Hello! Nice to meet you, ${name}.`};
```
> Or remove the parenthesis if using a single parameter and remove the curly braces if using a single expression and that expression will be returned from the function. 

```js
const sayHello  = name => `Hello! Nice to meet you, ${name}.`;
```

---
___

**Q:** What is the role of _return_ inside the function body and how is it different from using console.log?

> **A:**  When a function utilizes a _return_ statement, it’s determining the value the function returns. If there is no expression after the _return_ keyword or no return statement at all, then the function will return undefined. When Javascript reaches the _return_ keyword, it goes outside the scope of the current function and gives the returned value to the code that called the function. Utilizing `console.log` simply prints to the terminal, but it's not doing anything outside of the function. In order to use the function, it’s important to declare a function within the scope (called _local scope_ or _function scope_ vs. _global scope_), from which it’ll be called. 

---

**Q:** What’s the difference between parameters and arguments and what happens if there are no parameters?

> **A:** When declaring a function, parameters behave like placeholders, while arguments are the values that are being passed in a function call.

> It’s also important to now that if the function changes the value of an argument, this change is not global in scope or in the calling function. In addition, with default function parameters, you can initialize parameters with default values if no value or undefined is passed. 

---