# Loops

**Question #1**
```
What is the most effective way to run the same code repeatedly without code below?
```
```js
text += bikes[0] + "<br>";
text += bikes[1] + "<br>";
text += bikes[2] + "<br>";
text += bikes[3] + "<br>";
text += bikes[4] + "<br>";
text += bikes[5] + "<br>";
```
**Answer**
```
For loops are useful when we want to run the same code repeatedly with different values.
```
```js
const bikes = ["Cannondale", "Specialized", "Trek", "Cervelo", "Pinarello", "Giant"];

let text = "";
for (let i = 0; i < bikes.length; i++) {
  text += bikes[i] + "<br>";
}
```

**Question #2**
```
For in loop
```
**Answer**
```
```
**Question #3**
```
While loop  
```
**Answer**
```
```
