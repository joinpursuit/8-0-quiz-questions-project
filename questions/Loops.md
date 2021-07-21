# Loops

**Q:** What are `Loops` in JavaScript and can you show what a `for loop` is? 

> `Loops` are used in JavaScript to perform repeated tasks based on a *condition*. *Conditions* typically return **true** or **false** when analysed. A `loop` will continue running until the defined *condition* returns *false*. Example Below of `for loop`

```js
let arr = [1, 2, 3]
for(i = 0; i <= arr.length; i++)
```
___

**Q:** What is a `while loop` in JavaScipt and can you show it?

> The `while loop` starts by evaluating the condition. If the *condition* is **true**, the statement(s) **is/are** executed. If the *condition* is *false*, the statement(s) **is/are** not executed. After that, `while loop` ends.

```js
let i = 1;
while (i < 5)
{
    console.log(i);
    i++;
}

/*Output:
1
2
3
4
5
*/
```
___

**Q:** What is a `do...while loop` in JavaScipt and can you show it?

> The `do...while loop` is closely related to `while loop`. In the `do...while loop`, the *condition* is checked at the end of the `loop`. 

```js
let i = 0;
do {
  i = i + 1;
  console.log(i);
} while (i < 5);

/*Output:
1
2
3
4
5
*/
```
___