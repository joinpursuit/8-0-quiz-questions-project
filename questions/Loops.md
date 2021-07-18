# Loops

**Question #1**
```
What is the most effective way to run the same code repeatedly without writing it multiple times?
```
```js

example:

txt += bikes[0]; //index pos 0
txt += bikes[1]; //index pos 1
txt += bikes[2]; //index pos 2
txt += bikes[3]; //index pos 3
txt += bikes[4]; //index pos 4
txt += bikes[5]; //index pos 5
```
**Answer**
```
For loops are useful when we want to run the same code repeatedly with different values. we are able to loop through a block of code a number of times. 
in the example below we see that the first statement (let i = 0;) is executed one time before the code block is executed. Our second statement (i < bikes.length;) then defines the condition for executing the code block and finally our 3rd statement is executed every time after the code block has been executed (i++).  
```
```js
const bikes = ["Cannondale", "Specialized", "Trek", "Cervelo", "Pinarello", "Giant"]; // Array listing the different bikes

let txt = ""; //string
for (let i = 0; i < bikes.length; i++) { // for loop 
  txt += bikes[i];
}
```

**Question #2**
```
How do we loop through the values of an iterable object?
```
**Answer**
```
We use "For Of" loops in order to loop through the values of any iterable object.
in the example below you can see that we use the constant variable "bikes" in order to loop through the array in our for of loop.
```

```js
const bikes = ["Cannondale", "Specialized", "Giant"]; //array of bikes

let txt = ""; 
for (let x of bikes) {
  txt += x;
}
```
**Question #3**
```
Using while loops we know that we can execute a set of statements as long as the condition is true.
Based on the code in the block below. what do we expect the result to be & why?
```
```js
i = 1
while i < 5:
  print(i)
  i += 1
  

```
**Answer**
```js
/*  
    1
    2
    3
    4
*/
```
```
this result printed because our while loop increments our iterator by 1 each time as it loops 4 times until it stops executing before the 5th loop.  
```
