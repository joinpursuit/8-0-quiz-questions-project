# Functions

**Q1:** Name 3 important differences between arrays and objects.

> One crucial difference is the way that their stored information is accessed. Information is accessed from an array by using index numbers which are assigned to each value. Information from an object is acquired by referencing a key, which is similar to an index number of an array, but does not need to be a numerical value and therefore is not ordered. 

> A second difference is the notation used to reference their values. Object values are referenced through the use of dot notation and bracket notation with quotation marks, while array values are referenced through only bracket notation and numerical values.

> A third difference are the different methods applicable to each. A prime example of this would be the fact the objects do not have a length, therefore the .length method wouldn't work.
---

**Q2:** Imagine an amateur programmer named Jimmy is trying to add to the array, eminem, and print Eminem's full name. Name some mistakes being committed below and give a suggestion to improve Jimmy's code.

```js
let eminem = ['Marshall', 'Mathers'];
eminem[middleName] = 'Bruce';

return eminem;
```
> A mistake being committed is that Jimmy is using improper notation to add to `eminem`. Since `eminem` is an array, he would have to use the `.splice()` method to insert bruce between marshall and mathers. Proper notation for that line would be `eminem.splice(1, 0, 'Bruce');`. Then to print just the name, he could do `return eminem[0] + eminem[1] + eminem[2]`.

---
**Q3:** If you wanted to store multiple choice questions and answers for a quiz within a data structure, which would be more suited for the job: object or array? Give a reason why.

> For this kind of data storage, you might find it necessary to use a mix of both. You could use an object to have each question be a nested object within, containing a key-value pair for questions, answer choices as an array, and answer key. For example:

```js
{
question: "What is the capital of United States?",
choices: ["Washington D.C.", "New York", "California", "Washington"],
answerIndex: 0
};

```

---

**Q4:** How would you log the string `'pen'` nested in this object?

```js

let storage = {
  "desk": {
        "drawer": "stapler"
  },
  "cabinet": {
        "top drawer": { 
            "folder1": "a file",
            "folder2": "secrets"
        },
        "bottom drawer": "pens and markers"
  },
  "bigChest": ["backpack",  
              "pencilCase",
              ["pen", "pencil", "marker"]]     
};

```
> You would log the string with 
```js 
console.log(storage.bigChest[2][0]); 
```

