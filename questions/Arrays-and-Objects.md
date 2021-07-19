# Data Structures 


**1. What is the output of the following code?**

```js
const arr = [1, 2, 'Hello'];
arr[50] = 100;
console.log(arr.length);
```

<details>
<summary>Click here to see the answer</summary>

>**Answer: 51**
>The reason is that `JavaScript` places `empty` as a value for indices 3-49. Thus, when you set the value of the 50th index, you get the length as 51.
</details>

---

**2. What is the output of the following code snippet?**

```js
let arr = [1,2,3,4,5,6,7];
const newArr = arr
arr = [];
console.log(newArr);
```

<details>
<summary>Click here to see the answer</summary>

>**Answer: [1,2,3,4,5,6,7]**
>When we carry out the above (containing arr = []) you create a new array and break the old reference. Thus, newArr has no effect on it since it is still pointing to the old array.

</details>

---

**3. What property tells you the length of a JavaScript array?**


<details>
<summary>Click here to see the answer</summary>

>**Answer:** The “length” property
</details>

**4. What will be the result of the code below?**
```js
const person = { firstName: "Barbara", lastName: "Liskov" };
person.awards = [];
console.log(person);
```

<details>
<summary>Click here to see the answer</summary>

>**Answer:** The “length” property
</details>