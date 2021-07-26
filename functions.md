# What is a Function?

Standard, repeatable tasks in computing, call for a type of "mini program," or small bit of code (instructions), designed to perform them. These mini-programs or "subprograms" are called **Functions** and are composed of a sequence of statements known as the function body.

[Values](https://developer.mozilla.org/en-US/docs/Glossary/Value) are able to be passed to functions which will accordingly return another expected value (potentially, in an expected order). A function is executed or invoked when "called" (more on that later). 

Some functions do not take any values or parameters at all and only result in an (expected) output. Considered "first-class objects" in Javascript, they are able to have properties and methods. This means they can be:

- Stored in a variable, object, or array
- Passed as an argument to a function
- Returned from a function

In other programming languages, a function can be a procedure or subroutine. With more modern applications, functions can be a complete program in and of itself, rather than the general notion of a “subprogram." 

# What is the Syntax of a Function?

How a function is written, or the "Syntax" of a function, includes a [keyword](https://www.w3schools.in/javascript-tutorial/keywords/#:~:text=ECMAScript5%20New%20Keywords-,What%20Are%20JavaScript%20Keywords%3F,that%20JavaScript%20provides%20to%20programmers.) and a name (to reference said function), followed by parentheses.

Names may contain letters, digits, underscores, and dollar signs (all of which are also true for variables).

Parentheses may include parameter names separated by commas. Function "arguments" are  values received by the function when invoked.

Finally, code executed by the function is placed inside curly brackets: {}. This is called the function body.

```
function name(param1, param2, param3) {

  //code to be executed
  
}
```

# How is a function "called?"

A function must be invoked or "called," in order to actually perform its specified task or action. "Calling" is a predefined [Method](https://developer.mozilla.org/en-US/docs/Glossary/Method) in Javascript: 

```
call( );
```

With this method, an object can use a method belonging to another object and can be used to invoke another method with an owner object as a parameter-also known as an ["argument."](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments)
