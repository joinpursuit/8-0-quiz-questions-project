# Loopies

**Q:** What types of `Loops` have we learned so far? 

<details>
<summary>Click here to see the answer</summary>

>**Answer:** Loop for, Loop while, Loop of, and Loop in. 
</details>

---

**Q:** If `process.argv` is `['hello', 'need sleep', 'git it.' 'hello and good night.', 'Wow', 'Yes!']` 

with the `for of` loop, what are we looping through? 

```js
    let input = process.argv; 
    const convertNum = input.slice(3); 
    

    for (const i of convertNum) {

}
```

<details>
<summary>Click here to see the answer</summary>

>**Answer:** 'it will be 'hello and good night.', 'wow', and 'Yes!.' 
</details>

---

**Q:**  What will be the role of the `continue` keyword in the following JavaScript `code` snippet?

```js 
while (a != 0)
{
   if (a == 1) 
       continue;
   else 
       a++;
}
```
**Now, take  a look at the following statements below**

1. The continue keyword restarts the loop
2. The continue keyword skips the next iteration
3. The continue keyword skips the rest of the statements in that iteration
4. The continue keyword breaks out of the loop

**Which statement(s) describes the role of `continue` keyword in the code above?**


<details>
<summary>Click here to see the answer</summary>

>**Answer:** *C* is the only statement that is true about the keyword `continue`
 
>Instead of exiting a loop like the `break` keyword, the `continue` keyword moves to the next iteration from the place encountered. While the `break` statement breaks out of the loop.
</details>