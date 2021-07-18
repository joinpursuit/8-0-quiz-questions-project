# Functions

***Question 1:***
Can a function run after you declare it?

>Answer: No. You need to call the function if you want it to run.  Basically, declaring a function with your name for it doesn't make the code run.  You need to call it once it is declared. To call the function so it can run in your code, you need to type the function name followed directly by parentheses. For example, with this function:

```js
function dinosaurs() {
    console.log('T-rex')
}
```
The code won't run because the function was called.  But if you call your function with the function name or identifier `dinosaurs()` :

```js
function dinosaurs() {
    console.log('T-rex')
}
dinosaurs()
```
The code will run and should print in your terminal.



