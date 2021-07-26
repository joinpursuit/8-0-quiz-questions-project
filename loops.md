# What are Loops?

In JavaScript, loops are code used to perform repeated tasks based on a condition which more often than not, returns a "true or false" when analyzed. 

Loops are indispensible when we think in terms of business and situations in our every day lives. As passengers checking in for a flight at the airport or a customer checking out at the grocery store, loops are operating in every application and program ushering us through our days.

Getting back to the more technical, there are (3) loops which are most common. They are:

- **for**
- **while**
- **do while**

# How Do "for," "while," and "do while," loops differ?

## for
Loops through a block of code-or "iterated" a number of times.

## while 
Loops through a block of code while a specified condition is true-however testing the condition prior to executing any of its statements.

## do/while 
Also loops through a block of code while a specified condition is true but tests the condition after the statements have been executed within the loop.

# How is Code Looped?

- In terms of the standard for loop, the keyword **for**, is followed by parentheses.
- Inside the parentheses are (3) items, separated by semi-colons
- After which, curly braces that contain a block of code will run each time the loop iterates

Here is a standard **for** loop:

```
for (let cats = 0; cats < 3; cats++) {
  // Runs 3 times, with values of cats 0 through 2.
  console.log('I have many cats');
}
```