# Arrays and Objects
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
// At position 2, add 2 elements:
fruits.splice(2, 0, "Lemon", "Kiwi");
```
---  
```

  597 mkdir 8-0-quiz-questions-project
  598 cd 8-0-quiz-questions-project
  599 ls
  600  git clone https://github.com/Jalamang/8-0-quiz-questions-project.git
  601  cd 8-0-quiz-questions-project/
  602  cd questions
  603  touch arrays-objects.md 
  604  touch functions.md loops.md git.md github.md
  605  code .
  606  git add arrays-objects.md
  607  git commit -m "Arrays && Objects: What, why and how they are use"
  608  git push
  609 history | tail -n -10 >> arrays-objects.md
  ```

