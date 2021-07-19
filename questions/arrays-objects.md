# arrays and objects
**Q:** Given an array of numbers, how can we use an object to remove duplicated elements?

> Javascript objects are very useful and we can use them to solve some problems. As an object will only keep one key/value pair in the object, we can use that behavior to solve this problem. Having an empty object, we can iterate through the array using `for of` loop and add each element with the value true. Even if the program will try to add identical key/value multiple times, the object will keep just one. As example of solving this problem:
```javascript
let arr = [2,1,2,5,2,3,7,1];
let obj={};
for (let elem of arr) {
    obj[elem] = true;
}
Object.keys(obj);

```
`Object.keys(obj)` will return an array with no duplicated elements. In our example we will have `['1', '2', '3', '5', '7']`. We will just need to turn `string of numbers` to `numbers`.
---
**Q:** How can we use a function to create objects?

> There are many ways to create objects in javascript and the easiest way is to use an object literal. In some cases, this way will not help. We can then use `constructor functions` or `factory functions` to create them. `Objects contructor functions` will use the keyword `this` and also it is good practice to start the first letter of that function in upper-case. On the other hand, `factory functions` will just return an object and its naming convention is camel case. It does not need the `this` keyword but generate different objects by providing different arguments to the function. It is very important to remember that in order to create an object with the `constructor function` we need to use the keyword `new` before the function name.
**Note:** `this` in the `constructor function` does not have a value. After creating new object using the constructor, `the value of this` will be that new object. After creating an object, it can be modified by adding new properties and methods and its change will not affect other objects created from the same constructor. To make a general change, it has to be done in the function constructor. Javascript also has built-in constructors such as `new String`,`new Date` etc.
---
**Q:**  How do you explain: in javascript almost everything is an object?

> All javascript values are objects except primitives (number, string, boolean, null, undefined, bigint, symbol). Objects are objects and arrays are objects because when we check `typeof` a given array, it will return `object`. Also, we can use array's indexes as their keys, and elements in the array as values, they are very similar. Functions are first-class objects because they can have properties like `.length`,`arguments` and methods. The big difference between regular objects and functions is that functions can be `invoked` or `called`. Also, Booleans, Numbers, Strings can also be objects if they are defined with the `new` keyword. All these said, it is valid to say: `almost everything is an object in javascript`.
--- 
**Q:** Define an iteration tool special for an array and an object.
- `for of` loop for an array,
- `for in` loop for an object.