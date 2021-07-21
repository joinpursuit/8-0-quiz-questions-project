# Arrays

**Q:** Update 'shots' in the array to 'Good luck remembering the night'.

```js
let party = ['beer', 'wine', 'shots', 'whiskey', 'cocktail'];
```

> **Answer**:

> `party[2] = 'Good luck remembering the night'`

> `party[2]` will select the element positioned in index 2, which is `'shots'`, then the equal sign will update the element to `'Good luck remembering the night'`. 

---

**Q:** What is the sum of all *numbers* in the array?

```js
let randomDataTypes = [17, 38, "NANI!", [], false, 'the', 1975, {}];
```

> **Answer**:

> 
```
let result = 0; 
for (let i = 0; i < randomDataTypes.length; i++) {
  if (typeof(randomDataTypes[i]) === "number") { result += randomDataTypes[i] };
}
console.log(result);
```

> First the variable `result` is declared and set to `0`. A `for loop` is used to iterate through the array using an if statement to check if each passing element is equal to the data type number by utilizing `typeof`. As it iterates through the array, it will add any element that is number to the variable result which is equal to `0`. Finally, result is console.logged which is equal to `2021`

---

# Objects

**Q:** How do you print out `10474` to the console?

```js
let fellow = {
  age: 25,
  address: {
    city: 'Bronx',
    state: 'NY',
    zip: {
      code: 10474
    }
  }
}
```

> **Answer**:

>
```js
console.log(fellow.address.zip.code);
```

> Using dot notation(`.`), we access `10474` by first accessing the address using `fellow.address`, which returns `{ city: 'Bronx', state: 'NY' }`, then `{ city: 'Bronx', state: 'NY' }.zip` will return `{ code: 10474 }`, then `{ code: 10474 }.code` will finally access `10474`

---

**Q:** How do you add `france: 'Gael Monfils'` in the topPlayers object?

```js
let tennis = {
  type: 'sport',
  topPlayers: {
    spain: 'Rafael Nadal',
    switzerland: 'Roger Federer'
  }
}  
```
> **Answer**:

>
```js
tennis.topPlayers.france = 'Gael Monfils';
```

> `tennis.topPlayers` accesses the topPlayers object. Using dot notation (`.`), with the new key name `france` will add the key and will insert `'Gael Monfils'` as the value into the `topPlayers` object. 

---