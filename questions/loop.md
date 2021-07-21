***Q***
The code below does not work! What’s wrong? Look closely because it’s really small.


```js

function countLambos(carsSpotted) {
console.log("lamborghini parade! Lets count them!");
for (let lambo = 1; lambo > carsSpotted; lambo++) {
console.log(`${lambo} lamborghinis!`);
}
}

countLambos(20)
```

>the loop won’t be able to increment because condition has “lambo” as greater than the “carsSpotted”. Change the “>” to “<=“ and you will see 20 Lamborghinis!

***Q***
Which loop is mostly used for boolean values?

A. While
B. For
C. Boolean
D. True Loop

>A while loop is mostly used for boolean values, where it loops until it is false.

***Q***
What is the primary benefit of using loops?

A. They allow you to run the same code over and over, without the extra syntax.
B. They are infinate.
C. They will print the same output over and over, allowing you to save for later.

>The answer is A. Loops can execute code over and over based on a condition. Why write a console.log 100 times when you can just..

for(let i = 0; i < 100; i++)
