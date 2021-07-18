# Loops
**Q1:** How can we move through a list of valus in an array?
>`Loops` are used to move through arrrays over and over again. They're different kinds of loops that can do diffrent kinds of things.
```js
// Examlpes of loops
for (let i = 0; i < arrays.length; i++)
while (num <= 10)
for (let element of arrays)
```
---
**Q2:** How does is a for i loop structured and how do the parts work?
>The `for i` loops starts with the for statemant followed by three statements in `()` parentheses. The statements are separated by `;` semicolons.
```js
for (let i = 0; i < arrays.length; i++)
// The firts statement creates the variable i.
// Second statement defines the condition for the loop to run.
// Third statement increases the value each time the code is executed.
```
---
**Q3:** Can the for i loop be written differently?
>The `for of` statment can creat a loop in less text.
```js
for (let element of arrays)
// let creats a variable.
// of iterates value.
```