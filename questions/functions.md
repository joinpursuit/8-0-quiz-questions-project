## Functions:

### 1) Describe what a function is called before it is defined.

```
One can call a function before it is defined, this is called hoisting. (A function defined with expression syntax or ES6 arrow function will be assigned to a variable, and any variable used before it is defined will have the value of 'undefined'.)

When a javascript file is executed, the JS interpreter reads through the whole file top to bottom, assigning values and figuring out what needs to be run when. Function declarations are then ‘hoisted’ or lifted to the top of the file, essentially reordering them. This is not what happens behind the scenes but it makes it easier to think about this way.
```
### 2) Describe the difference between returns and side-effects.

```
When you call a function that has a return statement in it, it produces a new value that can then be used later. A parameter can be considered an input, returns are considered outputs.
Returns produce a new value from the function. To use that value, we have to capture it in a variable, otherwise it disappears. If we don't return anything from a function, the function automatically returns ‘undefined’.

Side effects; a function has ‘side effect’ when it affects something outside of its own scope. One example is changing the value of a variable that was defined outside the function.
Because of referencing the variable directly by name, and because ‘said variable’ was declared outside the function, it can affect the value. Sometimes you want to do this on purpose, it is better to fix your code so that it doesn't do this.
```

### 3) Summarize scope for variables inside and outside of functions.

```
Think of scope as a sort of hierarchy, about where variables are accessible and where they are not. The takeaway here is that variables declared in a function are only accessible inside that function. Variables declared outside a function are called ‘global’ and they can be accessed and modified from any function.

A variable declared inside a function has ‘local’ scope, and a variable not declared inside a function has ”global” scope. So a variable with “local” scope is only available inside that function. A variable with “global” scope is available inside or outside the function.  

If we create a variable inside a function with the same name as a global variable - the function will only be aware of the local one. This, however, will not change the value of the global variable. Also If we have a function inside of a function, the rules still apply, but now we have more than just two scopes. 
```