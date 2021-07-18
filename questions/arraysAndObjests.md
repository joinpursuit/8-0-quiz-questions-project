**Q:** What ia an Array and how to access array elements? Give an example.
```
Array is a varialbe which can hold more than one value at a time. 

Here is an example:
```
```js
const fruits = []; // Creating an array
fruits[0] = "orange"; 
// Index position zero, the first element in the array is "orange"
fruits[1] = "apple"; 
//Index position one, the second element in the array is "apple"
fruits[2] = "kiwi";
//Index position three, the third element in the array is "kiwi"

//console.log(fruits); --> Print: the array of fruits which including "orange","apple","kiwi".
```
---

**Q:** What are push() method and splice()method? How could they work in an array? Give an example for each method.
```
The push() method adds one or more elements to an array and returns the new length of the array.

The slice() method returns a shallow copy of a portion of an array tin to a new array object selceted from start to end (end not included) where start and end represent the index of items in that array. The original array will not be modified.

Here are the examples:
```

```js
const animals = ["dogs","cats","sheep"];
// The original array which includes three elements
const moreAnimalsLength = animals.push("pigs","monkey");
// Adding two more elements at the end of the original array
console.log(moreAnimalsLength);
// Print: 5 (returns the new length of the array.)
console.log(animals);
// Print: [ 'dogs', 'cats', 'sheep', 'pigs', 'monkey' ] (Logs a new array by adding two elements.)
```
```js
const animals = ["dogs","cats","sheep","pigs","monkey"];

console.log(animals.slice(2));
// It will print the new array which starts from the index position 2 in the original array til the end.
// Print: ["sheep","pigs","monkey"];
console.log(animals.slice(2,4));
//It will print the new array which starts from the index position 2 in the original array til the end, but end not included.
//Print: ["sheep","pigs"];
```

---

**Q:** Take a look at the following example. Try to get access to one of value in the abject, create and log a greeting sentence.
```
Here is the example:
```
```js
const studentInfo = {
    name: "Jane",
    gender: "male",
    interest: "dancing",
    age: 22,
}
// Getting access to the valuse "Jane" by using the name of the object + . + the key name
console.log(`Hi,${studentInfo.name}! How are you doing today!`)
// Creat and log a greeting: "Hi,Jane! How are you doing today!" 
```

