What is a loop in JavaScript?
JavaScript Loops are used to repeatedly run a block of code - until a certain condition is met. 
What are the different kinds of loops?
for - loops through a block of code a number of times
for/in - loops through the properties of an object
for/of - loops through the values of an iterable object
while - loops through a block of code while a specified condition is true
do/while - also loops through a block of code while a specified condition is true
what is the syntax for a for loop in Javascript?
for (statement 1; statement 2; statement 3) {
    code block
}
Statement 1 is executed (one time) before the execution of the code block.
Statement 2 defines the condition for executing the code block.
Statement 3 is executed (every time) after the code block has been executed.
Example
for (let i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
From the example above, you can read:

Statement 1 sets a variable before the loop starts (let i = 0).
Statement 2 defines the condition for the loop to run (i must be less than 5).
Statement 3 increases a value (i++) each time the code block in the loop has been executed.