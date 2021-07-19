# Arrays & Objects

**Q:** What is an Object and how do we access object properties?
 
> **A:** An Object is a collection of properties describing an item in key-value pairs surrounded by curly brackets known as the object literal like so:

```js
let newObj = {key: value} 
```

> An object is a grouping of things. We can access them via dot notation, bracket notation and variables. For example, with variables, you’re putting the value into Objects, so that if you change anything in Objects, you do not change the variable. If a key-value doesn't exist, it's undefined. As long as it's a non-value, JavaScript still considers it having a value (_undefined, null, NaN, -Infinity, empty brackets, 0_), but it is not possible to have a key without a value or a value without a key. 

> While it is common to use dot notation, there are cases where it is best to use bracket notation. Bracket notation is not as easy as dot notation but it does have benefits. For example, if the property you want to access has dashes (-) in it, dot notation will not work. In those cases, bracket notation would be better as shown below and as long as we pass in something that is a string, we can use bracket notation with variables. 

```js
let obj = {
  first-Name: “Sal”,
  last-Name: “Rey”,
};

console.log(obj["first-Name"]); 
//> “Sal
```
---
---

**Q:** What are Arrays and how do they relate to Objects?

> **A:** An array is a collection of similar items inside square brackets `[ ]`. If you have a list of things, you usually use an Array. But Arrays and Objects are closely related to each other. 

> When you check on the terminal the data type of an array via `typeof []`, the result is `Object`. An Array is really a special kind of Object. An Array is actually a collection of keys in an Object. For example, both the elements in Arrays and the values in Objects can be accessed using bracket notation. In an array, the elements are stored as properties with the index numbers (zero-based index) as property names (eg. `array[0]`). This is due to the fact that dot notation does not work with numbers. 

> For Objects, however, the data type that can be used as keys is almost always a string (it can also be symbols, though very rare). So you can’t call an object with its index like you can in Arrays; it wouldn’t be the index, it’d be the key. 

> Objects and Arrays can both store any data type as a value, combine values or lookup values (use a variable as a value). You can also do an expression like a value but you cannot do a statement within an object literal. 

> Also, Arrays have a .length property and the order of things is important, while there is no order in Objects - just keys. The key is like the equivalent of the index for an Array. Indexes are very clear cut. It starts at 0 and is numerical that goes on consecutively until its last element. Another key thing to note about Arrays is that, unlike Objects, Arrays are built-in iterables because they have default iteration behavior. 

---
---
**Q:** What is the outcome of following and why?

```js
const firstArray = [A, B, C] 
const secondArray = [D, E, F]

let result = firstArray + secondArray 

console.log(result);
```

> **A:** The output is: “A,B,CD,E,F”. The reason for this output vs. A, B, C, D, E, F is based two things. First, the elements in the arrays are converted to strings. Then, when this happens and the strings are then concatenated, you’re just combining the two strings. Here’s how:

```js 
[A, B, C] + [D, E, F]
    
// call toString()
[A, B, C].toString() + [D, E, F].toString();

// concatenation
“A,B,C” + “D,E,F”;

//> (“A,B,CD,E,F”);
```

> It’s important to note that it’s probably best to not use this method to correctly combine two arrays. To combine, consider this approach:   

```js 
[…[1, 2, 3], ... [4, 5, 6]]

//> [ 1, 2, 3, 4, 5, 6 ]
```

> In JavaScript, the ellipsis or three dots shown above are called the _Spread Syntax_ or _Spread Operator_, which allows objects that have iteration behavior such as Arrays to be expanded.

 

---
