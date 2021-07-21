# Arrays & Objects

**Q:** What is an `Array` in JavaScript and can you show it? 

> An `Array` is a unique *variable*, which can hold more than one value plus different types of value's as well. Every value is assigned with a *numeric index* starting with **zero** and each value is also called an *element*. See example below.

```js
// Numeric index are 0 is 1, 1 is true, 2 is 3, 3 is "four"
let arrOfNumbers = [1, true, 3, "four"]
// The element values are 1, true, 3 "four"
```
___

**Q:** What is an `Object` in JavaScipt and can you show it?

> An `Object` is a standalone entity that holds multiple values in terms of properties and methods. `Object` it’s most important data-type and forms the building blocks for modern JavaScript. An object can be created with figure brackets {…} with an optional list of properties. A property is a “key: value” pair, where a key is a string (also called a “property name”), and value can be anything.

```js
let pursuit = {
    instructor: "Greg Testo",
    location: "New York City",
    subjectMastery: "JavaScript"
}
```
___

**Q:** Can you show how an `Array` and `Object` work together?

```js
let cohorts = [
    {
        "hectorIlarraza": 8.2,
        "carlosMoran": 8.2,
        "laibaSajid": 8.2,
        "isidroMolina": 8.1,
        "joshBorbon": 8.1
        "namePingLouie": 8.2,
        "class": "Grrrrrr"
    }
];

console.log(cohorts[0].class);
```

> By using the *cohorts* `Array` you'll need to get the first *element* in the `Array` and then get *class* property from the `Object`. 
___