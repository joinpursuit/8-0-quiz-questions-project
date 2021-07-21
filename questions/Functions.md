# Functions

``
### Question: What will the function return?

``js
function text(text) {
    return console.log(text)
};
text(undefined)

a. undefined
b. undefined as a string
c. error
d. text

> Answer: The answer will be 'c. error' because of a typo on the return statement. Seems simple, however there could be confusion if there isn't an understanding of how functions work.  Based on what seemed to be common issues around parameters, data types, and noticing minor details.  Also unlike other words, undefined will not return a reference error without quotes.
This question could probably be repurposed to a few other qustions with some minor changes.
---

`` 
### Question: What are the key parts and syntax to building a function?
``js

function example(parameter) {
  contents
}


> Answer: A basic function consists of the function keyword, an optional function name, optional parameters, and the desired functionality/contents.  



``
### Question: Can you use a function within a function? What does the code below show

Example:
``js

function count(number) {
  console.log(number)
  let newNum = number - 1
  if (newNum > 0) {
    count(newNum)
  }
}
count(5)


> Answer: Yes and prints 5,4,3,2,1 seperately, and we're getting into the realm of recursive functions.  The function just continues to call itself until the condition is no longer met. Probably an interesting way to expose people to it, and using quizzes to introduce new material seems okay since the scores don't really matter, so long as people take the time to think it over.