# Java-Script Array and Objects Quiz

**Q1:** How can one find how many elements are within an array?

> You can access the ```.length``` property of an array to get the number of elements in the array.

---

**Q2:** How would one access the number ```110``` in the array declared below? 
```js
var array = [
  [1,9,3],
  [4,5,18],
  [7,8,90],
  [[10,110,12], 13, 14]
];
```

> To access the number ```110``` in the array below one must use bracket notation twice as the first element in the array is also an array (nested array). ```array[0][1]```.

---

**Q3:** How would one access the bulk price of the object below?
```js
const plum = { 
  color: 'Purple',
  price: {
    'bulk price': '$2/kg',
    smallQty: '$5/kg'
  }
};
```

> To access the property of a nested object one can use either dot or bracket notation. If keys have spaces bracket notation is required. ``` plum.price["bulk price"] ```