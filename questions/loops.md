# Loops

## Question # 1:
What is the important of looping?

### Answer:
Looping allows you to quickly and easily handle a coding situation repeatedly. For example, if you want to console.log each element in an array, you don't have to put many lines of console.log. With a loop that takes about few lines, it will repeatedly console.log the elements in an array easily.
```Javascript
let arr = [1,2,3,4,5];

// You don't want to console.log like below.

console.log(arr[0]);
console.log(arr[1]);
console.log(arr[2]);
console.log(arr[3]);
console.log(arr[4]);


// Rather than console.log each element and changing the index, you can just write a loop.

for (let i = 0; i < arr.length; i++) {
    console.log(arr[i]);
}
```
---------------
## Question # 2:
Please name the parts that make up a for loop based on the code snippet below.
```Javascript
1   let arr = [1,2,3,4,5];
2   
3   for(let i = 0; i < arr.length; i++) {
4       console.log(arr[i]);
5   }
```

### Answer: 
**for**: The "for" will announce to Javascript that you will be writing a for loop. It is a keyword.

**()**: The open and close parenthesis right after the keyword "for" will be the an expression.

**let**: You will declare with the "let" keyword on line 3. 

**i**: This is the variable you will be using to represent each element.

**=**: This is an assignment operator.

**0**: This will be the first element in the array meaning the zero is the index number in an array. 

**;**: The semi-colan is used to seperate the statements in the expression.

**<**: This is the less than sign. You will compare the index with the length of the array.

**arr.length**: This will be the length of the array.

**i++**: This will increment by one. It is called the iteration. After the code block has been executed it will move on to the next element.

**{ }**: This is the code block. It will be where you write the instructions to do for each element.

**let i = 0;**: This statement is the initializer. Meaning this is where the loop will start in the array.

**i < arr.length**: This statement is the condition. That means the loop will keep running until it reaches the end of the array.

---------------
## Question # 3: 
What is the difference between the "for...in" loop and "for...of" loop?

### Answer: 
The [for...in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in) and [for...of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of) loop, both loops through the object. The difference is that the "for...in" loop will loop through the properties of an object. Meaning it will display the key and value pairs. The "for...of" loop will loop through the values of the object. 

---------------
## Question # 4:
Loops are an important part of JavaScript program. Please name the different type of loops JavaScript supports and what each loop will do.

### Answer: 
**for loop**: The "for" loop loops through a block of code with a certain number of times.

**for...in loop**: The [for...in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in) loop loops through the properties of an object.

**for...of loop**: The [for...of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of) loop loops through the value of an object.

**while loop**: The [while](https://www.w3schools.com/js/js_loop_while.asp) loop loops through a block of code while a specific condition is true.

**do while**: The [do while](https://www.w3schools.com/js/js_loop_while.asp) loop loops through a block of code while a specific condition is true. However, the "do while" loop will run at least once before checking if the condition is true. Then it will repeat the loop. 

---------------
## Question # 5: 
In the "for loop", the iteration statment in the code below "i += 2;". Does the following code run correctly? If so, what does this code do?
```Javascript
let arr = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15];

for(let i = 0; i < arr.length; i += 2) {
    console.log(arr[i]);
}
```
### Answer: 
The code will run correctly. This code will log out the numbers 1, 3, 5, 7, 9, 11, 13, 15. In the code snippet, rather than incrementing by one index, it is incrementing by 2 indexes. So it is logging out the numbers that are increased by 2. 