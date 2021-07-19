# Functions


**Q:** Given the following `function`, what will be the console output when yes() is invoked(called)?

```js
function yes (a,b,c) {
    console.log(a + b + c);
}

yes('We can do this!', 'Fail forward!');
```
<details>
<summary>Click here to see the answer</summary>

>**Answer:** "We can do this! Fail forward! undefined" will be logged to the `console` because when a `function` executes, any arguments that are not passed-in have a value of: `undefined.`
</details>


---


**Q:** Given the following `fuction`, what will be **`logged`** to the console?

```js
function findCar (brand, price) {
    if (typeof brand !== 'string') {

        return "Please enter the name of your desired car brand."

        console.log("Contact us if you need any assistances!")
    }
}
```

<details>
<summary>Click here to see the answer</summary>

>**Answer:** Nothing will be logged to the `console` because when a `return` statement is used in a `function` body, the execution of the `function` is stopped. 

>Think it this way, there is a box and it is closed. If it is closed, we can't add more, right? `return` is like closing a `function`, telling you that we end this `function` here! don't add more! **This is the end!**

>Try moving the `console.log` above the `return` statement and see if the `console.log` prints out the message inside ()
</details>

---

**Q:** Select all of the statements below which are true.

1. A JavaScript `function` doesn't have to be defined with `function` keyword, but it is highly recommend.
2. `Functions` must have at least **one** `parameter` inside ()
3. When JavaScript reaches `return` statement, the `function` will stop executing.
4. `Functions` can be executed as many times as you want


<details>
<summary>Click here to see the answer</summary>

>**Answer:** 3 and 4 are the only true statments. A function must be defined with the `function` keyword. Your functions don't have to have parameters. 
</details>