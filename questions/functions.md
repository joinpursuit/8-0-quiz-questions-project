# Functions

## Question # 1:
According to the [MDN Website](https://developer.mozilla.org/en-US/docs/Web/JavaScript), **Functions** are one of the fundamental building blocks in JavaScript. When we code to solve a problem, you will be surprised that there are many ways to arrive to the solution. Therefore, there will also be different ways to write a **JavaScript Function Syntax**. How many ways can you write a function syntax to add two numbers?

### Answer:
1. **Function Declaration**: This function syntax is the most common way of writing a function especially for those who are new to JavaScript.
```Javascript
function add2Nums(a,b) {
    return a + b;
}
```
2. **Function Expression**: This function syntax allows you to take the function and put it in a variable. You can use const or let. In this scenario, you can use const.
```Javascript
const add2Nums = function(a,b) {
    return a + b;
}
```
3. **Arrow Function Expression**: This is a compact way of writing traditional function expression. However, according to the MDN website, it is limited meaning it can't be used in all situations.
```Javascript
const add2Nums = (a,b) => {
    return a + b;
}
```
4. **Concise Arrow Function Expression**: This syntax is even more compact than the Arrow Function Expression. You can use this only if you use only one line of code.
```Javascript
const add2Nums = (a,b) => a + b;
```
---------------

## Question # 2: 
Sometimes you would want to pass an infinite number of parameters. So when calling the function, you are allowed to pass in an infinite number of arguments. There are currently two ways to pass an infinite number of parameters. Tell me what are those two ways and how are they different from each other.

### Answer: 
1. **Arguments Object**: It is used in ES5 and can not be used in any arrow functions. The **arguments** object is not an array so you will need to convert it to an array. You can use the [Array.from](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from) method.

2. **Rest Parameters**: It is used in ES6 and can be the easiest way to write a infinite number of parameters. It uses the same syntax as the [spread operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax) meaning all you have to write on the parameter is "..." followed by the parameter name. You can use the [rest parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters) on array methods like [map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map), [sort](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort), and [filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter).

---------------
## Question # 3:
It's important to know the parts of a function syntax and what it is doing inside the function. According to the code below, please name the parts of the function and explain what each line of code is doing.
```Javascript
function numToAdd (a,b) {
    const firstNum = a;
    const secNum = b;
    let total = firstNum + secNum;
    
    return total;
}

numToAdd(1,2);
// 3;
```
### Answer: 
**function**: To write a function, you will have to declare that you are going to write a function by typing the "function" keyword. 

**numToAdd**: Is the name of the function.

**(a,b)**: Inside the parenthesis are two parameters. The parameter names are usually the values of the variable. As a side note, it is optional to include parameters. 

**{ }**: When you write a function using the function keyword, you must always use the curly braces to write a function. You write your code inside the curly braces.

**const**: "const" is a keyword you can use to declare a variable. The "const" keyword is used only if the value is constant, meaning the value will never change.

**firstNum**: This is the variable name.

**secNum**: This is the variable name.

**total**: This is the variable name. In this case, it represents the total value of "firstNum" and "secNum" variable.

**=**: This is the assignment operator. Please don't get confused with "=="(aka loosely equal) and "==="(aka strictly equal). The loosely equal will perform a type conversion meaning if you were to compare the string "1" with the number 1, it will return true. Unlike loosely equal, the strictly equal will not do any type conversion. If the string "1" and the number 1 was to be compared, it will return false. It is because it is also comparing the data type. 

**a**: This is the value of the variable "firstNum"

**b**: This is the value of the variable "secNum"

**let**: "let" is the keyword used when declaring a variable. Unlike the "const" keyword, the "let" keyword would allow you to change the value, meaning you can reassign the value. 

**+**: The add symbol is an addition operator. In this case, it will add the values of "firstNum" and "secNum" together. Also, the "addition" operator is the only operator that has more than one properties. Meaning, the addition operator can be used for concatenation. You can concatenate strings. "Concatenation" is when you add strings together or when you combine more than one strings to make a sentence or sentences.

**return**: This is a keyword used in a function. It will return the result of whatever calculation or evaluation you wrote in your code. Almost 99% of the time, you must use "return" in your function. Not only that, you can only return one value in a function. However, there is a way you can return multiply values in a function by putting the values in an array or object. Then you can return an array or an object.

**numToAdd(1,2)**: After you write your function code, to make the function run, you must call the function. To call it, you write the function name followed by the parenthesis. If there are paremeters in your function, then you must input the arguments inside the parentesis. The arguments are "1" and "2". The "1" is for the parameter "a" and "2" is for the parameter "b". Notice the order of arguments must match the order of the parameters. If you were to switch the arguments around, then "2" would be "a' and "1" would be "b". In this case it is alright but usually, you should follow the order of the parameters. 

**// 3**: The "//" sign is used to comment one line in your code. The "3" is written to show that the result should return 3. When the code runs, javascript will ignore the comments. An alternative to writing more than one line of comment is by typing: 
```Javascript
/*
write your comment
on this
line
*/
```
---------------
## Question # 4:
When we write code, we almost always need the console to see what is being shown. This allows us to check if the code we are writing is correct or that it is doing what we want it to do. We either **console.log** part of the code or **return** the result. So, what is the difference between console.log and the return statement? In what situation would you use one over the other?

### Answer:
**console.log**: It is one of the methods from the [console object](https://developer.mozilla.org/en-US/docs/Web/API/Console) that outputs messages. It will print and display any message to the user. You would often hear people say "log to the console." You can pass in a number, string, function, a concatenated mix of data types, and variable names as long it's been defined first. Usually, you would use "console.log" to debug your code.

**return**: You would only use the keyword return when you are inside a function and when you want the result from the function after doing some kind of calculations. It would show you the result or a value when the function is called. If you put a return in a code block or a loop, it will immediately stop running the code if the conditions have met and will return a value. That means it will exit out of the loop or a block of code and out of the function itself.

---------------
## Question # 5:
When you write code, legibility is really important. When I say legibility, I meant, if the code is formatted correctly. Below, are code snippets. Please take the time to look at it and see if the code is formatted correctly, is missing something, or you need to change something in order for the code to work correctly.

1. Is this code correct? If not, how would you fix it?
```Javascript
1   Function AddAllNum(a,b) [
2         let total = a,b;
3       Return total = a,b
4   ]
```
2. Is this code correct? If not, how would you fix it?
```Javascript
1   funcsion addAllNum(a, b) { let total=
2                                  a+b;
3   return=total 
4   ]
```
3. Is this code correct? If not, how would you fix it?
```Javascript
1   function add-All-Num[a,b] {
2   const total = 3;
3   if(a<5) {
4   total=+ a
5   }
6   else (a>=5){
7   total =+ 10
8   }
9   return total;
10  }
11
12  function add-All-Num(5,2);
13  /* this function call should return a number */
```
### Answer:
1. The keyword "Function" should be lowercase. The name of the function should preferably be camel cased. You should have a pair of curly braces rather than square brackets. You should add "a + b" rather than "a,b" on line 3. The "return" keyword should be lowercase. You do not need "= a,b" on line four. Finally, you put a semi-coloan after line 4.
```Javascript
1   // This code snippit is not correct.
2   Function AddAllNum(a,b) [
3   let total = a,b;
4   Return total = a,b
5   ]
```
```Javascript
1   // This code snippet is the correct way of writing the function.
2   function addAllNum(a,b) {
3       let total = a + b;
4       return total;
5   }
```
2. The keyword "funcsion" is spelt incorrectly. It should be "function". You should put the let variable on line 3. On line 4, you do not need an assignment sign and you should replace it with a space. Include a semi-colan after the word total on line 4.
```Javascript
1   // This code snippet is not correct.
2   funcsion addAllNum(a, b) { let total=
3                                  a+b;
4   return=total 
5   ]
```
```Javascript
1   // This code snippet is the correct way of writing the function.
2   function addAllNum(a,b) {
3       let total = a + b;
4       return total;
5   }
```
3. The function name ideally should be camel cased followed by a parenthesis rather than a square bracket. You should put a tab on line 3. "total" should be a let variable because "total" will be updated. Line 4 should be tabbed and the total on line 5 should be double tabbed. After the word "total", should be "+=" rather than "=+". You should put a semi-colon after the letter "a" on line 5. The curly brace on line 6 should be tabbed. "else" should be tabbed. You do not need the expression "a>=5" on line 7 because it is an else statement. Else statments don't need parenthesis. It is like a catch all statement. "total" on line 8 should be double tabbed. Line 9 should be tabbed. To call a function, you don't write the word "function" on line 13. You will remove it and make sure the function name on line 13 matches the function name on line 2. Line 14, is a multi-line comment. You can use it on one line, however it is preferably to make two forward slashes for a one line comment and a "/* your comment */" for a multi-line comment.
```Javascript
1   // This code snippet is not correct.
2   function add-All-Num[a,b] {
3   const total = 3;
4   if(a<5) {
5   total=+ a
6   }
7   else (a>=5){
8   total =+ 10
9   }
10   return total;
11  }
12
13  function add-All-Num(5,2);
14  /* this function call should return a number */
```
```Javascript
1   function addAllNum(a, b) {
2       let total = 3;
3       if (a < 5) {}
4           total += a;
5       } else {
6           total += 10;
7       }
8       
9       return total;
10  } 
11  
12  addAllNum(5,2);
13  // this function call should return a number
```
