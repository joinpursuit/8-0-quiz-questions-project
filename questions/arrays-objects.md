# **ARRAYS & OBJECTS**

<br>
<br>

## **Q. How can we access an element in an array?**

> **A.** You can access elements in an array by using their index.

example:
```js
const myArr = [1, 2, 3];

console.log(myArr[0])
//output: 1
```
<br>
<br>

## **Q. How can we replace an element in an array with another value?**

> **A.** We can find the index of the number being replaced and set it equal to the new number.

example:
```js
const myArr = [1, 2, 3];

myArr[0] = 3;

console.log(myArr);
//output: [3, 2, 3]
```
<br>
<br>

## **Q. How can we change an array into a string?**

> **A.** The `.join('')` operator can be used to turn arrays into strings.

example:
```js
const myArr = [1, 2, 3];

console.log(myArr.join(''));
//output: "123"
```
<br>
<br>

## **Q. How can we access an value in an object?**

> **A.** We can access a `value` in an object by using the `.` operator and `key`

example:
```js
const object = {firstName: 'Sam'};

console.log(object.firstName);
//output: "Sam"
```
<br>
<br>

## **Q. How can we add key and value property to an object**

> **A.** We can use the object's `name` followed by the dot `.` operator, the name of the new `key` and set it equal to the `value`.

example:
```js
const object = {firstName: 'Sam'};

object.lastName = 'Harris';

console.log(object);
//output: {firstName: 'Sam', lastName: 'Harris'}
```
<br>
<br>

## **Q. How can we access an element in a arrary which is inside of an object**

> **A.** We can use the object's `name` followed by the dot `.` operator, the name of the `key` holding the array and the `[index]` of the element in the array.

example:
```js
const object = {firstName: 'Sam', lastName: 'Harris', hobbies: ['Soccer', 'Gaming', 'Cooking']};

console.log(object.hobbies[0]);
//output: "Soccer"
```
