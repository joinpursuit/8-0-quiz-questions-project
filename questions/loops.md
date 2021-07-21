# LOOPS

**Question #1**
Create a for-loop that prints out "Javascript" to the console 6 times starting from 0:
> **Answer:** We start our loop at `0` with the increment of `1`, until we reach the number `5`.
```js
    
       // looping from i = 0 to 5
        for (let i = 0; i <= 5; i++) {
          console.log("JavaScript");

```


**Question #2** Create a for-loop statement that will create this output to the console:
```js
2
4
6
8
10
12
14
16
18
20
```
> **Answer:** We start our loop at `2` with the increment of `2`, until we reach the number `20`.
```js
for (let i = 2; i <=20; i += 2) {
    console.log(i);
}
```

**Question #3** Why does this code throw a `ReferenceError` to the console?

```js
let i = 1, a = 8;
// while loop from i = 1 to 8
while (i < b) {
    console.log(i);
    i+= 1 ;
}
```
> **Answer:** The variable `b` is not defined. We are using the variable `a` which is defined to the number `8`.
