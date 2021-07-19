# Arrays & Objects

**Question #1**

```
Imagine you are running a script that only returns the first name of our key value pair. What property accessor is used to access 'firstname'? 
```
```js
const bootCamp = {
  firstname: 'Pursuit',
  lastname: 'fellowship'
};

console.log(bootCamp['firstname']);
```
**Answer**
```js
//returns 'Pursuit'
```
```
in the example above Bracket notation was used to access the property of the bootCamp object by writing the name of the object followed by brackets[] and inserting the property name as a string inside of it.

```
**Question #2**
```
B & H Photo in New York City has hired your company to fix a bug in their p.o.s system and they need your help accessing the correct elements in their list of high end cameras. With the help of index find the location of the Contax cameras.

```
```js
const cameras = Array ();

cameras[0] = 'Nikon'
cameras[1] = 'Yashica'
cameras[2] = Array ("Canon", "Leica", ["Contax"])
```
**Answer**
```js
console.log(cameras[2][2][0])
```
```
we console log our variable name and insert the index position of each string inside of brackets [].
```
**Question #3**
```
Without running the code below what do you think will happen when we console log iceCream?
```
```js
let iceCream = ["Rocky Road", "Vanilla", "Chocolate"];
iceCream.push("Cookies & cream");
console.log(iceCream);
```
**Answer**
```js
//result

["Rocky Road", "Vanilla", "Chocolate", "Cookies & cream"]
0: "Rocky Road"
1: "Vanilla"
2: "Chocolate"
3: "Cookies & cream"

length: 4
```
```
using the .push() method we are able to add an additional flavor of ice cream(Cookies & Cream) to the end of our existing array of ice cream flavors.
```
