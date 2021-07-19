# Arrays and Objects

## Question # 1:
What are the different ways to create an array

### Answer:
1. The basic way
```Javascript
const arr = [];
```
2. Array Constructor
```Javascript
const arr = new Array();
```
3. Array.from
```Javascript
let arr = Array.from({length : 5});
// note that it will create 5 elements that are undefined in the array "arr".
```
4. If you were to merge arrays into a new array, you can use the spread operator.
```Javascript
let arrA = [1,2,3,4,5];
let arrB = [6,7,8,9,10];
let arrC = [...arrA, ...arrB];
```
5. You can also create an array using "Array" and if you pass in one argument, it will create the empty items. In this case, it will create 3 empty items. Please note that empty items does not mean it is undefined. They are just empty and it has the length of 3 items.
```Javascript
let array = Array(3);
```
6. You can use Array.of however it can only create an array with a single element in it. 
```Javascript
let arr = Array.of(3)
```
---------------
## Question # 2:
What is the difference between an index and an element in an array?

### Answer: 
**element**: An element holds only one value. Depending on the size of the array, it can hold only that amount of values. When I say size of the array, I meant the length of the array. If you want to know how many elements is in an array, you would use the ".length" method. If there is 1 element in the array, the length will be one. If there is no element in the array, the length will be zero, meaning the array is empty.

**index**: On the other hand, an index is the location of where the element is located on the array. The array is zero-indexed meaning, the array location will start at 0. It will increment by 1 on the next index. The index position will always be one less than the length of the array. For example, if the length of the array is 10. The last position on the array will be a 9. It is because 0 - 9 are the index numbers and there are 10 elements in the array coounting 0 is the first element.

---------------
## Question # 3:
Let's say you have an array. You want to modify the array. What methods can you use to add or remove an element to an array?

### Answer: 
1. **Array.push**: The [Array.push()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push) method allows you add an element at the end of the array. 
2. **Array.unshift**: The [Array.unshift()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift) method allows you to add an element at the beginning of the array. 
3. **Array.pop**: The [Array.pop()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop) Unlike the "Array.push" and "Array.unshift" methods, this method allows you remove the last element from the array.
4. **Array.shift**: The [Array.shift()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift) method allows you to remove the first element in the array.

---------------
## Question # 4: 
What are some common and popular Array methods one would use in their JavaScript program? Please explain what each method does.

### Answer: 
**.length**: The [.length](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length) method returns a number of elements in that array. 

**.sort**: The [.sort()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) method sorts the elements in the array. By default, it sorts in ascending order. However, it will convert the elements into strings. 

**.includes**: The [.includes()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes) method will return either true or false whether the array of elements includes a certain value.

**.splice()**: The [.splice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) method will change the actual array. It will remove or replace exisiting elements or even add new elements in the actual array. It will modify the original array.

**.filter**: The [.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) method will create a new array will all elements that pass a test you provided. The test provided will be a function. So in the array, if an element passes the function test, it will add that element to a new array.

---------------
## Question # 5: 
There are two ways of accessing an object. Below is a code snippet. How would you access "dad" using both ways? How would you access "Anderson" using both ways? When would you use one over the other and vice versa. What method would you use to display all the keys in the object? 
```Javascript
const person = {
    fullName: {
        firstName: "Jamie",
        lastName: "Anderson",
    },
    age: 15,
    gender: "female",
    favColors: ["pink", "purple", "blue"],
    hasSiblings: true,
    familyMembers: ["mom", "dad", "brother"],
}
```

### Answer: 
1. **Dot Notation**: To access "dad" using Dot Notation.
```Javascript
let father = person.familyMembers[1];
```
2. **Bracket Notation**: To access "dad" using Bracket Notation.
```Javascript
let father = person["familyMembers"][1];
```
3. **Dot Notation**: To access "Anderson" using Dot Notation
```Javascript
let last = person.fullName.lastName;
```
4. **Bracket Notation**: To access "Anderson" using Bracket Notation.
```Javascript
let last = person["fullName"]["lastName"];
```
5. When you use bracket notation, you are allowed to access properties that contain special characters or when the characters in the string contain spaces in between. When you use dot notation, it is faster and a lot more easier to read. However, you won't be able to access the properties that contain special characters. 
6. To display all the keys in the object, you can use "Object.keys()"
```Javascript
Object.keys(person);
```
