# Arrays and Objects

**Q:** How to differentiate between methods that are destructive and non-destructive?

> A: Test by console logging, and act according by declaring and assigning new variables to the non-destructive ones.

---

**Q:** Differences between `.splice` and `.slice`?

> A: Splice can work with the given array, takes arguments of index position, delete count, and a replacement element.  
Slice removes elements and returns a new array with the removed elements, takes starting and ending index, and also takes a replacement argument.

---

**Q:** What will the following code snippet log to the console? And why?

```javascript
const programmer = {
  firstName: "Grace",
  lastName: "Hopper",
};
const result = programmer[firstName];
console.log(result);
```

> A: It will be undefined because firstName is not a variable it's key that is a string, thus should be in quotes.

---
