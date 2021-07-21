# Loops

**Q:** What are the different types of for loops?

> **Answer**:

> 
* **For** - loops through a block of code a number of times
* **While** - loops through a block of code while a specified condition is true
* **For In** - loops through the properties of an object
* **For Of** - loops through the values of an iterable object


---

**Q:** What does the following code print to the console?

```js
let words = ["Courage", "the", "Cowardly", "Dog"];
let scaryShow = "";
for (let i = 0; i < words.length; i++) {
  scaryShow += words[i] + " ";
}
console.log(scaryShow);
```

> **Answer**:

> `Courage the Cowardly Dog` will print to the console. We let `scaryShow` variable equal to an empty string. The for loop will iterate through the `words` array and add them to the empty string within `scaryShow`.

---

**Q:** Convert the following code to a for loop?

```js
names += fellow[0]
names += fellow[1]
names += fellow[2]
names += fellow[3]
names += fellow[4] 
names += fellow[5]
```

> **Answer**:

>
```js
for (i = 0; i < fellow.length; i++) {
names += fellow[i];
}
```

> A `for loop` will iterate through the array at each index within the array `fellow`. This is a much more efficient way to write code.

---

**Q:** What does the following code print to the console?

```js
let num = 9000;
while (num <= 10000) {
  console.log('It is over ' + num + '!!!');
}
```
> **Answer**:

> `It is over 9000!!!` will repeat forever

> This is called an `infinite loop`. This happens because the code is repeatedly checking if the value of num is smaller than 10000. If it is smaller, it will log the value of num, and then check again. Since the value of num never changes, the code will just keep logging `It is over 9000!!!`, until the computer runs out of memory (or your scouter malfunctions and breaks.) 

---