**Q1:**  What is the difference between an array literal and object literal?
    
<details>
<summary>Answer</summary>

>The first one that might come to mind is syntax. An array literal uses square brakets whereas an object literal uses cruly brackets. We create array to store values in order whereas objects are created to store and collect properties of an object.  
</details>

<br>

**Q2:** What will be the result of the code?

```javascript
const person = { firstName: "Barbara", lastName: "Liskov" };
person.awards = ["Most Valuable Performer", "Most improved performer"];
console.log(person.awards[0]);
```

<details>
<summary>Answer</summary>

>"Most Valueable Performer"

>In line 1 we see that an object literal was created. In line 2 a key value pair is being added to the object called person. Line 3 log the value of key awards at index 0.
</details>

<br>

**Q3:** List five array methods or properties and describe what they do?

<details>
<summary>Answer</summary>

>Answers are not limited to the following

>.pop() removes the last element of an array and returns that element

>.push() add one or more elements to the end of an array and returns the new length of the array

>.join() creates and returns a new string by concatenating all the elements of an array

>.slice() returns selected elements in an array as a new array

>.length returns the length of a string
</details>