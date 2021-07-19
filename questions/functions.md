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

***Question 2:***
What will log in the terminal and why?

```js
function rapLyric(greet, name) {
  console.log(`${greet}, my name is, ${name}.`);
}

rapLyric();
```
>Answer: `Undefined` will print in place of the given parameters and look like this:

```js
undefined, my name is, undefined.
```
Since there are no strings in the function caller `rapLyric()`, javascript has nothing to pass through the function and prints the above code when it runs.  When we put a value or argment inside of `rapLyric`, it will look like this:

```js
function rapLyric(greet, name) {
  console.log(`${greet}, my name is, ${name}.`);
}

rapLyric('Hi', 'Slim Shady');
```
When we do this, it will print in the terminal `Hi, my name is, Slim Shady.`

***Question 3:***
In the following code, what kind scope is it an example of and why:

```js
let carnivore = 'T-rex'

function dinosaurs() {
  let carnivore = 'raptor';
    console.log('T-rex')
}
console.log(carnivore)
```
>Answer: This is an example of global scope because the variable `'T-rex'` was declared oustide of the `function dinosaurs()`. Even though the variable `'Raptor'` is declared inside the function body, doing `console.log(carnivore)` outside the function body prints `'T-rex'` into the terminal. 


