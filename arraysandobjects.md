# What are Objects

Javascript is an object-oriented language and thus, most things are objects in JavaScript (even Arrays which we get to in the next section)! Objects essentially are a collection of data and/or functionality-usually consisting of variables and functions (called properties and methods when inside objects). Defining and initializing a variable are usually how creating an object happens. 

const building = {};

# What are Arrays

As stated in the previous section, arrays are objects in JavaScript ([global objects](https://developer.mozilla.org/en-US/docs/Glossary/Global_object), in fact). As apps evolve and become more powerful with the addition of audio and video manipulation, being able to quickly and easily read and write raw binary data (which arrays provide a mechanism for) is imperative.

Arrays are list-like, grow and shrink dynamically, can have any JavaScript value and can be mutated (depending on what one is looking to accomplish with the array). Neither their length nor the types of their elements are fixed and their data can be stored at non-contiguous locations in the array. Typed Arrays differ from normal arrays in that they are [iterable](https://exploringjs.com/es6/ch_iteration.html#ch_iteration) and contiguous. All of their elements have the same type while normal Arrays can have holes (or indices). Typed Arrays cannot. More differences can be viewed [here](https://exploringjs.com/es6/ch_typed-arrays.html).

# What Makes Objects and Arrays So Special?

Objects are liable to change and can store a collection of data as opposed to just a single value. Arrays are liable to change also and can be used to store a list of values. 

## When to Use Objects

Objects represent practically anything that has characteristics, these characteristics are called properties and they consist of a key and a value which can be accessed, added, changed, and removed:

```
var object = {
  key: 'value'
};

var car = {
  model: 'Subaru',
  year: 1995,
  used: true
};

```

## When to Use Arrays

Arrays are used when it's necessary to create and store a list of multiple items (ie: a collection) which can be accessed in order to add and remove items in a single variable. They may contain [primitive data types](https://developer.mozilla.org/en-US/docs/Glossary/Primitive) or other Arrays! 




