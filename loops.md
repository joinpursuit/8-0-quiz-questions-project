# Loops

**Question 1:** On the Assessment Lab the following contast was given for a series of questions: 

```js

const products = [
  {
    id: "o8HTX2dbn",
    name: "Flash 18 Pack",
    brand: "REI Co-op",
    priceInCents: 3995,
    sizes: null,
    inStock: true,
    colors: ["Black", "Castlerock", "Cinnamon Stick", "Deep Marine"],
  },
  {
    id: "jxCeWz7hy",
    name: "Ultralight Dry Sack",
    brand: "Osprey",
    priceInCents: 2500,
    sizes: ["30L", "20L", "12L", "6L"],
    inStock: true,
    colors: ["Electric Lime", "Shadow Grey", "Tropical Teal", "Poppy Orange"],
  },
  {
    id: "IJK8vIUxG",
    name: "Refugio 28L Pack",
    brand: "Patagonia",
    priceInCents: 8900,
    sizes: null,
    inStock: true,
    colors: [
      "Black",
      "Forge Grey",
      "Classic Navy",
      "Mojave Khaki",
      "Smolder Blue",
    ],
  },
  {
    id: "mIqVMUzn5",
    name: "Ulvo 23 Pack",
    brand: "Fjallraven",
    priceInCents: 12500,
    sizes: null,
    inStock: false,
    colors: ["Black", "Red Gold", "Mountain Blue"],
  },
];
```

Given the previous infomation, The following syntax will have an error. What is it and why? 

```js 
function logAllNames(products) {

for (let id = 0; id < products.length; id++ ){
  let product = products[id];
  console.log(product.brand + product.name)
  ```

>Answer: The `console.log` contained a common error. In Javascript white space character is still counted as a characterazation a simple fix is (product.brand + "" + prodct.name)
---
**Question 2:** When should you use a (for) loop and (while) loop in the JavaScript challenges?

>Answer: In general, you should use a `for loop` when you know how many times the loop should run. If you want the loop to break based on a condition other than the number of times it runs, you should use a `while loop.` In the `For loop` you MUST create a new variable, thats not true for the `While loop`.
---

**Question 3:** What would be a simpler way to write the following problem? 

```js text += puppies[0] + "<br>";
text += Puppies[1] + "<br>";
text += Puppies[2] + "<br>";
text += Puppies[3] + "<br>";
text += Puppies[4] + "<br>";
text += Puppies[5] + "<br>";
```

>Answer: A simple `For Loop` can list out the number of puppies and simplify the problem: 

```js 
for (let i = 0; i < puppies.length; i++) {
  text += puppies[i] + "<br>";
}
```