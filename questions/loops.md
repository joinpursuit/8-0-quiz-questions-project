**Q:** What is Loops? Give an example of one kinds of loops.

```
JavaScript Loops are used to repeatedly run a block of code until a certain condition is met.
The javaScript for statement consists of three expressions and a statement.

Here is an example of For Loop:
```

```js
let allNumbers = 0;
for (let i = 0; i < 10; i++ ) {
    allNumbers += i;
}
//In the for loop, setting a variable before the loop starts (let i = 0). Then, defining the condition for the loop to run (must less than 10). Next, increasing a value (i++) each time the code block in the loop has been executed (add up all the numbers and the output will be 45. The number 9 will be added at the end, stop by 10).
```

---

**Q:** Give an example of For Of statement. And explain what will log at the end.

```js
const gettedScore = [88, 99, 100, "all numbers",{name: "Lili", gender: "female"}];

for (let everyPart of gettedScore) {
   console.log(everyPart); 
   // logs every element in the array which including the numbers, the string, and the object {two key-value pairs inside}.
}
```

---

**Q:** How to modify an array by using for loops? Give an example.

```js
let arrayOriginal = [];

for (let i = 0; i < 3; i++) {
// Setting a loop that runs until i < 3 is no longer true, and then print tha arrayoringinal array to the end of each iteration.
    let newArry = arrayOriginal.push(i);
    console.log(newArry);
/**
The output shows how the array updates with the new values.    
--> [0]
    [0,1]
    [0,1,2]
*/
}
```



