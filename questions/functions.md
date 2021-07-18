# functions

**Q:** What is `arguments` in javascript functions and how is it useful?

> arguments is a built-in object in javascript functions. It is a array like object because it has the length property and has indexes as keys.
What i mean is illustrated in these lines of code:
```javascript
function myFunction() {
    console.log(arguments);
}
console.log(device(2,3,6));
```
When we run this, the output will be: `[Arguments] {'0' : 2, '1' : 3, '2' : 6 }`. But it is not an array, it is an object. It does'nt have any other array properties or methods except `.length` and in this example, `arguments.length` will return 3, the number of arguments passed when we invoked the function.
**Note:**
* This object is only available inside a function. That means when we try this `console.log(arguments.length);` outside the function we will get a reference type error: `ReferenceError: arguments is not defined`.
* This object used be access differently by using arguments as a function property. That means if we have a function named `myFunction`, we could access it by doing `myFunction.arguments`. But this way is deprecated and *we shouldn't use it anymore.*
> `arguments` can be very useful because we don't have to define our function with parameters in order to use them in our function. We can still use it to access any arguments passed to our function when it was invoked and do some arithmetic operations. And also its `.length` property can be very helpful.
**Note:**
In case some people worry how can we then know how many parameters a function was defined with? *We can use the function property `.length` to know exactly how many parameters a function has. And it is accessible outside a function.*
---
**Q:** What is the difference between javascript `function call()` method and `apply()`?

> In javascript, there is a difference between call a function and invoke a function even though sometimes these terms are used interchangeable. That means when we write a simple function to do a specific task, we are supposed to use the term invoke. `Call a function` is a more complex term.
A function that belongs to an object is ussually called a method. `Call()` and `apply()` are javascript predefined methods and work very similary by allowing us to use a method on different objects. As example:
```javascript
const obj = {
    fullName() : function() {
        return this.firstName + " " + this.lastName;
    } 
};
const person = {
    fistName : "Mukayila",
    lastName : "ALAO"
};
const anotherPerson = {
    fistName : "Ali",
    lastName : "BABA"
};
```
In this case, we can do this:
`obj.fullName.call(person);` or `obj.fullName.apply(anotherPerson);` and the first one will return `Mukayila ALAO` and the second `Ali BABA`. These two methods work very similarly but they do have a difference. 
*Their difference is the way they accept arguments:*
- `call()` accept arguments separately
- `apply()` accept arguements in an array.
As example, when we change our method `fullName` to take two parameters we can have:
```javascript
const obj = {
    fullName() : function(age, profession) {
        return this.firstName + " " + this.lastName +". I am "+age +" and i work as " + profession;
    } 
};
```
As our method has two parameters, the way to `call()` or `apply()` will change:
`obj.fullName.call(person, 32, "software engineer");` or `obj.fullName.apply(anotherPerson, [32, "software engineer"]);`.
**Note:**
The keyword `this` used inside obj is the way javascript refers to the object in which properties or methods belong to.
---
**Q:**  What are javascript closures?

> `Closures` are the fact that an inner function accesses variables in an outer/parent function. In other words, a closure gives you access to an outer function's scope from an inner function. When it comes to data privacy, they play an important role. Closures are useful in hiding implementation detail in javascript. They can help to create private variables or functions.
As example:
```javascript
function add(a,b) {
    let variableC = 10;
    function addAgain() {
        console.log(a+b+variableC);
    }
    return addAgain;
}
let resultFunc = add(5,5);
resultFunc();
```
In this example, `resultFunc` will grab a reference to `addAgain` function which makes it a function. Normally after a function has completed its execution, its local variables are deleted. But using closures can help us keep those variables alive, that's why after `add(5,5)` finished, we're still able to access `variableC` and both arguments which give us `20` as result in this example.
---
**Q:** What is a `callback` function?

> A `callback` is a function passed as argument to another function and they can be very useful. It is important to remember that when using this concept, we should just pass the name of the function without the parentheses.

