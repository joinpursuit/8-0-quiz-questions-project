## LOOPS...

<p>&nbsp;</p>

## q 1. What are loops in javascript?
>**Answer:** JavaScript Loops are used to repeatedly run a block of code - until a certain condition is met. When developers talk about iteration or iterating over, say, an array, it is the same as looping.

<p>&nbsp;</p>

## Q 2. What is a while loop in javascript?
>**Answer:** The while statement creates a loop that is executed while a specified condition is true. The loop will continue to run as long as the condition is true. It will only stop when the condition becomes false. JavaScript supports different kinds of loops: for - loops through a block of code a number of times.
<p>&nbsp;</p>
*Example:*

```js  
let sum = 0;
let number = 1;

do {
    sum += number;         // -- body
    number++;              // -- updater
} while (number <= 50);    // -- condition

console.log("Sum = " + sum);    // => Sum = 1275

```
- The block following do is executed first and then the condition is evaluated. If the while condition is true, the block is executed again and repeats until the condition becomes false. This is known as a post-test loop as the condition is evaluated after the block has executed.

The do while loop is executed at least once whereas the while loop may not execute at all. The do while is typically used in a situation where the body of a loop contains a statement that generates a value that you want to use in your conditional expression

<p>&nbsp;</p>

## Q 3. What is a for loop?
>**Answer:** The for statement creates a loop that is executed as long as a condition is true. The loop will continue to run as long as the condition is true. It will only stop when the condition becomes false. JavaScript supports different kinds of loops: ... for/in - loops through the properties of an object.  

<p>&nbsp;</p>

*Example:*  

```js
let sum = 0;

for (let i = 1; i <= 50; i++) {
    sum = sum + i;
}

console.log("Sum = " + sum);    // => Sum = 1275

```
- It consists of three parts, separated by semicolons. The first is the initializer (var i = 1) which initializes the loop and is executed only once at the start. The second is a test condition (i <= 50). When a conditional expression evaluates to true, the body of the loop is executed. When false, the loop terminates. The third part is an updater (i++) which is invoked after each iteration. The updater typically increments or decrements the loop counter.

In a for loop, all three parts i.e. initializer, test condition, and updater are written together in a single line (called an iteration statement), whereas in a while, they're scattered and lie at different places. This makes a for loop more readable than a while loop and as a result, more easily maintainable.

So when do we use for and when while? If the number of iterations is known use the for loop. If you want to loop until a certain condition is met use the while loop.

<p>&nbsp;</p>

## Q 4 What is a break in javascript?
>**Answer:** The break statement terminates the current loop, switch , or label statement and transfers program control to the statement following the terminated statement.

<p>&nbsp;</p>

*Example* 

```js
var sum = 0;

for (var i = 1; i <= 10000; i++) {
    sum += i;
    if (i === 50) {
        break;    // immediately transfers control outside the for block
    }
}

console.log("Sum = " + sum);       // => Sum = 1275

```

- When an infinite loop is created intentionally, you can use a break statement to controls termination of the loop, like so:

<p>&nbsp;</p>

## Q 5. What is a continue loop?
>**Answer:** The continue statement terminates execution of the statements in the current iteration of the current or labeled loop, and continues execution of the loop with the next iteration.  

<p>&nbsp;</p>

*Example* 

```js
for (var i = 1; i <= 10; i++) {
    if ((i % 2) != 0) {
        continue;
    }
    console.log(i);     // => 2, 4, 6, 8, 10
}

```