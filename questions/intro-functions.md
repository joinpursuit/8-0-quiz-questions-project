**Q:** What is a function and how is it used in Javascript?

> Example: 
```
// This function will print 'man' and then print 'woman'
function logHumans() {
  let human = "man";
  console.log(human);
  human = "woman";
  console.log(human);
}
// logHumans will give the same output everytime it's called.
logHumans();
// prints 'man'
// prints 'woman'
```
Answer: A `function` allows you to expel upon a block of written code, name it, call upon it, and then execute it. In the example above the function `logHumans` returns the same output every time it is called.

---

**Q:** Give an example of the syntax used to declare a function?

> An example of syntax used to declare of function is:
```
function name (parameters) {
    //put function body here
}
//syntax example
function makeBed() {
    alarm("It's time to wake up!");
}
```
Reference: `Parameters` are made up names used to pass variables into a function. `Arguments` are the values assigned to the parameters.

---

**Q:** What are the best practices when naming functions?

> Answer: The best practices when naming a function are to keep the function name `unique`, `short`, and `descriptive`. Since function actions are names, make sure the function name is descriptive of what the function actually does!
