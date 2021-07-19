# Loops

**Q:** What are loops and what are the different types?


> **A:** Loops are like if statements, where if some condition is met, it’ll do some action, but it does so repeatedly. Here are several types of loops and an example of each:
- `for` statement has an initializing expression, if any, that can also declare variables. The condition expression will evaluate for a Boolean result, at which point if the value is false, the loop terminates. If this part is left blank, then the Boolean result is default True. 
```js
for (initialExpression [eg. let index = 0]; conditionExpression [x ; incrementExpression) {JavaScript Statements}
```
- `while` statement will keep looping until some condition happens or evaluates to true. 
```js
while (condition) {JavaScript Statements} 
```
- `for… of` will iterate or go through every single element in an Array for example, starting at index 0 to the end. However, if you wanted to start at the end of the array, then `for… of` wouldn’t work. You would use a regular `for` loop
```js
for (variable of object) {JavaScript Statements}
```
- `for… in` the loops happen over the enumerable properties (or keys/indexes) of an object
```js
for (variable in object) {JavaScript Statements}
```

---
---

**Q:** What are break and continue statements?

> **A:** A break statement is used to terminate a loop, specifically terminating the furthest in enclosing loop and transferring control to the following statement. To skip or terminate from a current iteration and continue the loop, a continue statement is used. However, it’s important to note that online break statement, a continue statement does not stop the whole loop from running. 

**Q:** What is a key difference with using `for` loop vs `while` loop and how are loops different from if conditional statements?

> **A:** In a `for` loop, it is iterating for example, through an array. But `while` loops until a condition is met. 
Also, `while` is like an if statement, where inside the parenthesis, you don't increment, you don’t declare variables, and only a condition goes. And while loops execute until the condition is met, if statements or conditional statements only perform the task once. 

---
---

**Q:** How is `for… in` used in Objects? 

> **A:**   Since there are keys in an Object, those keys are also the indexes (they’re enumerating keys).  With `for… in` loops, the iteration happens over the enumerable properties of an object. With `for… in` loops, you can add or access keys in an object to modify or return a result.  In the example below, the loops iterates over all of the object’s properties and prints out the property name and its value. 

```js
for (let key in obj) {
    console.log(obj[key], key)
```

---