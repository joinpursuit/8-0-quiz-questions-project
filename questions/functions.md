# Functions

**1. How would you declare a function?**
``` js
```
Use the "function" keyword to declare a function. What immediately follows is the function name. Immediately after that, inside of parentheses, is one or more parameters. After an opening brace, there is a function body, and an optional return statement, which will give the function a return value. Close the function body with a closing brace.
```
function functionName(parameters){

    return 
}
```


**2. How do you call a function?**

You write the name of the function and you put the parameter you want to pass through the function inside parentheses. Let's use the function above as an example: 

``` js
functionName(parameters)

```

** 3. What's wrong with the following function? (Note: the function is already declared) **

``` js 
functionName{}
    

```
This function won't work because there's no parentheses, empty or otherwise. Function syntax requires parentheses. Curly braces are only used in the function definition, and would also require parentheses for the parameter(s) in that case. 