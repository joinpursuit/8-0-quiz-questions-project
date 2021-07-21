## Loops

### Question: What are three types of for loops in Javascript?

Answer: Three types of for loops in javascript are for, for/in and for/of.


example:

for(let i = 0; i < 3; i++) {
    console.log(i)
    //output: 0 \n 1 \n 2
}
example:

const array = [1, 2, 3]

for(let element in array){
    console.log(array[element]);
    //output: 1 \n 2 \n 3
}
example:

const array = [1, 2, 3]

for(let element of array){
    console.log(element)
    //output: 1 \n 2 \n 3
}


### Question: When does a for loop end?

Answer: A for loop ends when the condition is met.

example:

const array = [1, 2, 3];

for(let i = 0; i < array.length; i++){
    console.log(array[i]);
    //output: 1 \n 2 \n 3
}


### Question: What happens if the condition in the for loop is never met?

Answer: The loop will run for ever it's condition isn't met.

example:

for(let i = 1; i > 0; i++){
    console.log(i)
}