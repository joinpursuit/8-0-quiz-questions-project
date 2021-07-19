# Function

**Q:** What is the purpose of `Function` in the JavaScript language?  

> A `Function's` purpose is basically wrapping a piece of program in a value to have many uses. It gives JavaScript the ability to structure larger programs, to reduce repetition, to weave names with subprograms and to isolate these subprograms from each other.

---

**Q:** How is `Function` used in JavaScript? 

> A `Function` is used to create an expression that starts with *keyword* `function`. They also have a set of *parameters* and a *body*, which contains the statements that are to be executed when the `function` is called. The `function` *body* that is created this way **absolutely** must be wrapped in braces, even when it consists of only a single statement. Also `functions` can have mutiple *parameters* or no *parameters* at all.

---

**Q:** Using what you learned about `Functions` earlier will the code below run.....yes or no? 

```js
function doYouUnderstand(thumbsUp, thumbsDown){
    let eureka = 100
    let nani = 50
        if(eureka > nani){
            return `Makes sense 😎 ${thumbsUp}!`
        } else {
            return `Grrrrrrr 😔 ${thumbsDown}!` 
        } 
}
doYouUnderstand("👍🏾", "👎🏾")
```
> Yes the code above will run correctly since the *parameters* are being called and the *if statements* are properly executing the *let* variables.  

---