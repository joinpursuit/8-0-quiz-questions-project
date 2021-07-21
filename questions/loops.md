# Loops

**Q1:** What are the two kinds of loops? How would you initialize a loop to print "`A mistkae that keeps being repeated is a choice.`" ten times with each type?

> The two kinds of loops are `for` and `while` loops. A while loop typically uses a variable defined beforehand to serve as a counter that is incremented or decremented until its conditional reaches a stopping point. A for loop functions very similarly to a while loop, but defines its own counter variable within the conditional brackets. It is a more condensed version of a while loop.

```js
// with a for loop
for(let i = 0; i < 10; i++){
    console.log('A mistkae that keeps being repeated is a choice.');
}
// with a while loop
let x = 0;
while(x < 10){
    console.log('A mistkae that keeps being repeated is a choice.');
    x++;
}
```

---

**Q2:** Jerry's favorite number is 7. How could you write a for loop to find every multiple of 777 between 0 and 7777?

```js

for(let i = 0; i < 7777; i++){
  if(!(i % 777)){
    console.log(i);
  }
}

```
> In this the loop, within the conditional is the range of numbers, 0-7777 and i++ to count through each whole number. The if statement's conditional checks for a situation where `i`is divisible by 777 without a remainder. The for loop ensures that this process is repeated until it reaches 7777. 

---
**Q3:** Consider the following code. What happens as a result of this and how could it be resolved?

```js
let num = 0;
while(num > 10){
    console.log(num);
    num++;
}

```

> The code breaks one of the fundamental rules regarding loops, avoiding an infinite loop. Something like this either causes an error or freezes your computer. To resolve this issue you simply need to set a proper endpoint for the loop, in this case you could change the > to < in the conditional. Alternatively, you could set num equal to a value higher than 10 and use num-- instead of num++.

---
