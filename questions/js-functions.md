# Java-Script Functions Quiz

**Q1:** What would the following code log?

```js
function sum(num1, num2) {
  num1 + num2;
};
console.log(sum(5,6));
```

> The call to the sum function with arguments 5 and 6 will return `undefined` because the function is missing a proper `return` statement.

---

**Q2:** Why would the following code return `ReferenceError: item is not defined`?

```js
function test() {
    var item = "apples";
  	console.log(item);
};
test();
console.log(item);
```

> Variables which are declared within a function, as well as the function     parameters, have local scope. That means they are only visible within that function.

---

**Q3:** Which of the following is the correct way to call the function below?

```js
const multiBy3 = (number) => {
  	console.log(3 * number);
};
```
> ```multiBy3(5)```
