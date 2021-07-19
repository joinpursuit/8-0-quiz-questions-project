# **LOOPS**
<br>
<br>

## **Q. What are three types of for loops in Javascript?**

> **A.** Three types of for loops in javascript are `for`, `for/in` and `for/of`.

<br>
<br>

example:
```js
for(let i = 0; i < 3; i++) {
    console.log(i)
    //output: 0 \n 1 \n 2
}
```

example:
```js
const array = [1, 2, 3]

for(let element in array){
    console.log(array[element]);
    //output: 1 \n 2 \n 3
}
```
example:
```js
const array = [1, 2, 3]

for(let element of array){
    console.log(element)
    //output: 1 \n 2 \n 3
}
```
<br>
<br>

## **Q. When does a for loop end?**

> **A.** A `for` loop ends when the condition is met.

example:
```js
const array = [1, 2, 3];

for(let i = 0; i < array.length; i++){
    console.log(array[i]);
    //output: 1 \n 2 \n 3
}
```
<br>
<br>

## **Q. What happens if the condition in the for loop is never met?

> **A.** The loop will run for ever it's condition isn't met.

example:
```js
for(let i = 1; i > 0; i++){
    console.log(i)
}
```


