# Function

**Q:** What is the use of isNaN function?

> isNan function returns true if the argument is not a number; otherwise, it is false.

```js
function milliseconds(x) {
  if (isNaN(x)) {
    return 'Not a Number!';
  }
  return x * 1000;
}
```

---

**Q:** what happen to the function after return value ?

```js

function myFunction(a, b) {
  return a * b;      
}

```

> When JavaScript reaches a return statement, the function will stop executing. If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

---

**Q:** what is wrong in this code below ?

```js
 functiON LetGo = (x,y) {
     let sum = x * y ;
     return sum;
 }
 function letGo (5,5);
```

> The function will not run because it will show a `syntax` Error .. The function is spelled wrong ..
