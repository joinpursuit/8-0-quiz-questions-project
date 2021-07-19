Question 1. Functions are objects???

- In computer programming, a **function object** is a construct allowing an object to be invoked or called **as if** it were an ordinary function, usually with the same syntax (a function parameter that can also be a function). Function objects are often called functors.

Question 2. What will this function return? And how can I get it to return the correct response?
```js
function text(text) {
    retun console.log(text)
};
text(cat)
```
a. undefined
b. undefined as a string
c. reference error 👈🏾 👈🏾
d. text
 - Because cat is undefined. To define cat put quotation marks around the argument "cat". 

 Question 3. Trick Question 
```js
function text(text) {
    retun console.log(text)
};
text("cat")
```
a. undefined
b. undefined as a string
c. reference error 
d. syntax error 👈🏾 👈🏾
- You would still get an error message because Return isn't spelled properly. Once return is corrected, console will print cat as a string.

