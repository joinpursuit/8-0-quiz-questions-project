# Loops
**Q:** What are the iteration structures in javascript and give an example for each?

> Loops are used in programming to execution a set of instructions repeatedly until some condition is met. 
let say you  want to print "Hello World" 10 times. You can do this using the example below
```js
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
console.log("Hello World\n");
```
but in an more elegant way, loops can handle this in just few lines. See below

## While Loop
This repeatedly runs a code block while a certain condition evaluates to true. It checks first before executing a code block.

```js
let i=1;
        while(i<=10){
        console.log("Hello World\n");
            i++;
        }
```

## Do While Loop
This works just like a while loop but that it atleast runs the code block once even if a condition is falsy. 

```js
 let i=1;
    do{
      console.log("Hello World\n");
            i++;
       }
    while(i<=10)
```
## For Loop
For loop operates just like while loop, it checks first before executing the code block. 

```js
for( let i=1; i<=10; i++){
      console.log("Hello World\n");
    }   
```

## For in Loop
This returns an index in arrays while in objects, it returns key of objects. Written like this

```js
for (variable name in object){
    statement or block to execute
}
```

## For of Loop
This runs through iterable objects and returns values of an array. Written like this

```js
for (const element of array) {
  console.log(element);
}
```


**Q:** When is _for loop_ preferred over while loop?

>  For loop is preferred when know the number of iterations to be made. 


**Q:** How can each element in an array be logged in a given number of times using for loop?

```js
Example
const array =[1, 3, 5]
console.log(array)
//>[1, 1, 3, 3, 5, 5]
```


>  This is done by wrapping one for loop in the other

```js
const array = [1,3,5]
for (let i = 0; i < array.length; i++){
    for (let j = 0; j < 2; j++){
        console.log(array[i])
    }
}
```


**Q:** What other mechanism is available that prevents a loop from running indefinitely other than it condition evaluating to falsy?

> Using one-token statement _**break**_ keyword does the magic. This stops the execution of the deeply nested loop that's been executed

## For instance
```js
while (1) {
  if (n < 0) 
  break;
  hello(n);
  n -= 1;
}
```

While loop runs forever in as much as the condition is true. So, in this case it will execute but in side the loop, if n is less than 0, the loop stops because of the keyword **break**: else it executes the _hello(n) function.

```js

  713  git add loops.md
  714  git commit -m "Loop structures"
  715  git push

```