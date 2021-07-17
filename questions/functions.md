# Functions
**Q:** How would you call a helper function?
> Within the first function you can call the second function using the function name and then invoking the paramater.
```js
functionNamehere(parameter){
    return stuff
}
```
<!-- for some reason it didn't  -->
---
**Q:** When should you console.log vs return in a function?
> Console log is for us to `read` rather than an output that can be tested compared to tests.
---
**Q:** Should you create a function with a let, var or a const?
> If it is let, then it can be reassigned and that could be a _serious_ *problem*.  We should **NEVER** use var! (it sucks) so therefore it should be a const.  We should not be able to reassign something as important as a const.
---  

```js
  620  git add functions.md
  621  git commit -m "Functions: When, why and how they are use"
  ```
