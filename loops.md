# Loops

**1. How do you declare a *for loop*? Give an example of the typical layout for a for loop.** 
```js
let variable = 5;

for(let i = 0; i < variable.length; i++){
    
}

```
The desired action will go inside the for loop body.

**2. What is a good use for looping in JavaScript?**
Looping is useful for repeating a block of code for a specific number of times, or while a certain condition is met. Looping is also great to check for a particular condition. 

**3. What is a *for… of loop*? Give an example of the syntax. When is it useful?**

A for...of loop is another type of loop which is even faster to set up than a traditional for loop. 

Example: 

```js
const cars = ['hyundai', 'honda', 'toyota', 'subaru']

for(const car of cars){
    if(car === 'honda'){
        return "There is a Honda available."
    }else{
        return "Sorry, there are no Hondas."
    }
}
```
You declare a variable which refers to the current index while you are looping. This is "car". In this example, the code is checking to see if one of the array indexes has the string, 'honda'. **for... of is a simple and fast way to loop through this array of strings to check for a value.**
