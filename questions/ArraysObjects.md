## ARRAYS AND OBJECTS

**Q** What are Characteristics of an Array? 

> Arrays have Elements and those elements have a specific Index postion. Arrays are recognizable since they use ```[]``` (Square Braces)

EX. 
```js
let numArr = [1, 2, 3, 4]; // [The values in here are Elements]
// [index position is 0 1 2 3]
```

--- 


**Q** What are the characteristics of an Object?

> Objects have key/value pairs. Objects are recognizable with ```{}``` (curly braces).

EX.
``` js
let person = {// wrapped in curly braces
  firstName: "Erika", /// key= 'firstName'  value = 'Erika"
  lastName: "Kim",
  age: 25,
  human: true,
};

```

--- 

**Q** How would you extract and print "Warzone" using Dot notation? 

``` js
let games ={
    playstation:{
        COD : 'Warzone',
        GTA : 'Online',
    },
    Nintendo:{
        Pokemon : 'Silver',
        animalCrossing : 'My Island',
    }, 
};

```
> ```Console.log(games.playstation.COD); // 'Warzone'```