### **Q:** What does the code below do?
```js
for (let i = 1; i > 0; i++){
    console.log(i)
}
```

> It will log every number in increments of 1 forever, or until the code is stopped.  This question should provide an example of a loop that has a condition that won't break.

### **Q:** How will the code below behave?
```js
let i = 0
while (i <= 95) {
    i = Math.floor(Math.random()*100)
    console.log(i)
}
```
> This loop will continue to roll until it hits the upper 5 percent of its bounds.  This question should provide exposure to a non incremental condition within a while loop.

### **Q:** What is the output of this code?
```js
let count = 0
for (let i = 0; i < 5; i++) {
    for (let j = 0; j <= 5 j++) {
        for (let k = 10; k > 5; k--) {//can change condition to k > i+j for a bit more thinking ---> 165
            count++
        }
    }
}
console.log(count)
```
> Current answer is 150. This question could be interesting exposure to nested for loops and a little bit of multiplication.  And kind of illustrating the exponential growth as loops get nested.