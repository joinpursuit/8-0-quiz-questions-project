**Q** There is a very important step missing from the function below. What crucial step is missing in the function below and what error message will you get?

```js
/function/ sayHello () {
    console.log("Hello " + cat)
}

sayHello()
```

>”Cat” is a variable, but it’s not defined. As a result, you will get the reference error “cat is not defined”. We can solve this by making “cat” a variable for example animal = “cat”

**Q** SCOPE is a very important part of functions. Look at the function below. Will you be able to log the message?

```js
let lamborghiniModel = “Aventador”;

Function logLamborghini() {
let lamboMessage = "Your lamborghini of choice is " + lamborghiniModel;
}

console.log(lamboMessage)

````

 

>NO. While, lamborghiniModel is declared in global scope, lamboMessage is declared INSIDE the  This means it only has local scope. In order to fix  we would have to move the console.log inside the func., or put lamboMessage into the global scope. 



**Q** What will be logged into the console should you run the following: 

```js

const name = "Oboe";
kind = "woodwind"

function whatKindOfInstrument(name, kind) {
console.log `${name} is a ${kind} of instrument.`
}



```

>Trick question of sorts! It while looks to the untrained eye that it would log “Oboe is a woodwind instrument”, in this approach you will get undefined. You need to RETURN the statement. 

So we create a return statement using string interpolation to store the values of const and kind and console log the result. 

The result that works is below. 

```js

const name = "Oboe";
const kind = "woodwind";
const instrumentNotice = whatKindOfInstrument(name, kind);

function whatKindOfInstrument(name, kind) {
return `${name} is a ${kind} of instrument.`;
}

console.log(instrumentNotice)
```


