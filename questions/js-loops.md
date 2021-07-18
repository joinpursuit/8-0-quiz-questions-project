# Java-Script Loops Quiz

**Q1:** What will be the result of the code block below?

```js
let interest = ['Mushrooms', 'Birds', 'Trees'];
 
for (let i = 0; i < interest.length; i++){

console.log(interest[i]);
};
```

> For each iteration of a loop the expression code block would run for each item of the array by accessing the length of the array. ```
Mushrooms
Birds
Trees```.

---

**Q2:** What is incorrect about the code block below?

```js
for (let i = 0, i < array.length, i++) {
    console.log(array[i]);
  };
```
> The initialization; condition; and increment step of the for looop, should be seperated by semi-colons not commas.
---

**Q3:** Please state and define the two additional built-in keywords that can be used within Loops (while,for,do).

> The ```break``` statement "jumps out" of a loop. While the ``` continue``` statement "jumps over" one iteration in the loop.