# Functions

**Q:** Is a `function` a reference type in Javascript?

> Yes! A `function` is indeed a reference type due to being a first class object in Javascript. They become a first class object in a programming language if a function can be passed as an argument to other functions, can be returned by another function and can be assigned as a value to a variable. 

---

**Q:** What will be the outcome of the following code?
```js
function bP(a, b) {
  return a + " " + b;
}

let x= bP("banana","party!");
console.log(x);
```
> banana party! <br><br>
Is what will be printed to the console. This is due to the variable being assigned to equal the function.

---

**Q:** What will be the outcome of the following code?

```js
function bP(a, b) {
  return a + " " + b;
}
let x = bP("banana" , "party!");
let y = (x.charAt(0).toUpperCase() + x.slice(1) + " 🍌  🎉")
console.log(y)
```
>Banana party! 🍌  🎉 <br><br>
Is what will be printed to the console.
This is due to the variable being assigned to x, then to y but with .charAt(0) which capatalizes the first letter and returns on the first letter, then the x.slice(1) returns everything after the first letter. With concatenation it gives you the full statement with the first letter capatilized.

---

**Q:** What will be the outcome of the following code?

```js

function bP(a, b) {
  return a + " " + b;
}
let x = bP("banana" , "party!");
let y = (x.charAt(0).toUpperCase() + x.slice(1) + " 🍌  🎉 ")
function ser(gregor){
  let begin = y.indexOf(x)
  let fin = begin + y.length;
  return y.substring(0, begin - 1) + y.substring(fin) + "Grrrrrrrrrr";
}

ser();
```
> ! 🍌  🎉 Grrrrrrrrrr <br><br>
Will be what is returned. <br>
This is due to the <br> `y.substring(0, begin -1)` <br> basically deleting the string while <br> `y.substring(fin)` <br> comes out to just <br>
`! 🍌  🎉 ` <br> and so <br> `Grrrrrrrrrr` <br> was just added to that in the return.