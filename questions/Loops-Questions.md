# Loops Questions

**Q:** What are the 3 requirements for a loop function?

- <details>
    <summary> Answer </summary>
     1- Initial value</br>
     2- Break condition</br>
     3- Update Exprecion 
</details>
</br>

**Q:** What are loops most ideal for?

- <details>
    <summary> Answer </summary>
     Lopps are most aideal when you are trying to hit every item in an object or hit an specific value of an array or object.
</details>
</br>

**Q:** What type of loop is the the one below?

```js
function printBedStats(bed) {
  let result = [];
  for (let key in bed) {
    let value = bed[key];
    result.push(value);
  }
  return result;
}

printBedStats({ brand: "Casper", rating: 3.9 });
```
- <details>
    <summary> Answer </summary>
     A for... in loop.
</details>
</br>