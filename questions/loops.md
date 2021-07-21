# Loops
​
**Q:** What is a for loop in Javascript? 
​
> The for loop is used to loop through the properties of an object generally within the confines of a function.
​
```js
​function banana(fruit){
    for (objectNewName name in objectOldName){
    statementAboutBananas;
    }
    return somethingAboutBananas;
}
```
​
---
​
**Q:** What will continue statement do in the following code ?
​
​
​
```js
function applesAreNotBananas(apple, banana) {
  if (apple == banana) {
    console.log("THIS IS NOT POSSIBLE!!!") continue;
  } else {
    console.log("Bananas FTW!");
  }

  return something;
}

```
​
> The `continue` statement skips one iteration in a loop. <br>The code has no loop therefore you get <br> `SyntaxError: Unexpected token 'continue' `.
​
---
​
**Q:** What does the for loop do in this code?
​
```js
const moneys = [1,69,22,36,419]

function bananaMoney(moneys) {
  let banana = 0;
  console.log(moneys)
  for (let money of moneys) {
    banana = money + 1;
    console.log(banana)
  }
  return banana;
}
```
​
> The `for loop` loops through the moneys array until the array.length is reached. <br>`banana` is assigned to `money + 1` and when `return banana` is triggered you get <br> `420` because it's the last number in the array and the other numbers created were not stored.
​
---

**Q:** What will the following code do?

```js

const aPeeling = ["b", "a", "a"]

function banana(aPeeling){
  bananaArr = [];
  let pushed = 0
  for(let peel of aPeeling){
  let peeled = peel.replace(/['"]+/g, '');
  pushed = bananaArr.push(peeled)
  }
  let mid = (Math.abs(bananaArr.join('')))
  return bananaArr[0] + bananaArr[1] + mid + bananaArr[2];
}

banana(aPeeling);
```
> It will return baNaNa. <br>
The `for loop` goes through the `aPeeling` array and `peeled` removes the `""` around the letters<br>
via `peel.replace(/['"]+/g, '')` <br>
It is pushed into `bananaArr` for storage. <br>
This process is repeated for all the letters.<br>
`let mid = (Math.abs(bananaArr.join('')))` tries to get a number value but cannot<br>
so it's output is `NaN` which means `Not A Number`. <br>
With a little concatination magic we get baNaNa.