# Example

**Q:** 

> A `ReferenceError` occurs whenever you are trying to access a variable you do not have access to. This could happen because the variable is misspelled or because the variable you are trying to access is out of scope.

---

**Q:** What general error will be thrown from the following code?

```js
const question = "What error will be thrown from the following code?";
const uppercase = question.split(" ").toUpperCase();
```

> The answer is `TypeError`. This is because when the `.split()` method is called on the `question` variable, it will evaluate to an array. The `.toUpperCase()` method must be called on a string, _not_ an array. Therefore, `.toUpperCase()` is being called on the wrong _type._

---

**Q:** The following code will throw a `SyntaxError`. Why?

```js
const temperatureInCelsius = 30;
if (temperatureInCelsius > 25)
  console.log("It is very hot today!");
}
```

> A `{` is missing after the closing parenthesis of the `if` conditional. While it is possible to write an `if` statement without curly braces, the closing `}` requires there to be an opening curly brace.

---
