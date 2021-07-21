# Arrays and Objects

**Question # 1:** How would you access and print`{shoeName: 'Air Max 95', color: 'Neon Green'}` from array given? **
```js
const nike = [
  {
   jordanBrand: "retros",
  shoes1: [
    {shoeName: "Jordan 1", color: "Red" },
    {shoeName: "Jordan 3", color: "Black" },
    {shoeName: "Jordan 5", color: "White" },
    {shoeName: "Jordan 11", color: "Cool Grey"},
  ],
},
{
  airMax: "original",
  shoes2: [
    {shoeName: "Air Max 90", color:  "Infrared"},
    {shoeName: "Air Max 1", color: "White" },
    {shoeName: "Air Max 95", color: "Neon Green"},
    {shoeName: "Air Max 97", color: "Silver"},
],
},
]
```


> The answer is:
  ```js
console.log(nike[1].shoes2[2])
 ```

 To print to console, we used "console.log". In order to reach the second object in the array we accessed `nike[1]`, then using dot notation accessed `shoes2[2]` to arrive to our destination retrieving `{shoeName: 'Air Max 95', color: 'Neon Green'}`.

---

**Question #2:** 
Which answer below shows an _object_?

1. var num = 23;
2. console.log("object")
3. {name: "Hannah", favColor: "Pink", name: "Erian", hero: "Batman}
4. function add(a,b);

> The answer is `C`, because it contains curly brackets, along with a key and a value with a colon separating them.

---
**Question # 3:** In the following code there is a syntax error. Find the syntax error so it can print correctly to the console.
```js
let shoes =[
    {shoeName: "Air Max 90", color:  "Infrared"},
    {shoeName: "Air Max 1", color :"White" }
    {shoeName: "Air Max 95", color: "Neon Green"},
    {shoeName: "Air Max 97", color: "Silver"},
]
console.log(shoes[0]);
```
> The syntax error in the code is missing a _comma(,)_ in second object of the array.
```js
{shoeName: "Air Max 1", color :"White" },
{shoeName: "Air Max 95", color: "Neon Green"},
```