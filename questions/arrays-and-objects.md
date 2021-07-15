#Arrays and Objects
**Q:** What data types can be in an array?
> **Everything!** Strings, numbers, objects, functions, booleans, (because functions are objects), even sub-arrays.
```js
["string",number, {key:value},[subArray],true,false,NaN,null]
```
---
**Q:** Why would you use an array?
> Arrays can contain multitudes of data types, and are easily accessed.  Therefore they can be accessed using an index, making arrays easy to work with.
```js
let sample = [1,2,3]
return array.length
// output === 3
```
---
**Q:** How do you manipulate arrays and objects?
> Common methods are push, pop, shift, and unshift.  With objects you can split. Splice, and slice.
```js
let sample = ["string",number, {key:value},[subArray],true,false,NaN,null]
sample.push("Hi")
sample.pop()
sample.shift()
sample.unshift("hi")
const fruits = ["Banana", "Orange", "Apple", "Mango"];