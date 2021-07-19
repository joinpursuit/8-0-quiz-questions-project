# Arrays & Objects Quiz

### Use this Array to solve questions 1 to 3.

``` javascript
1. const pets = [dog, cat, bunny, snake, fish, hamster] 
```

**1. What method could we use to determine how many elements we have inside of our array?**

<details>
    <summary>Answer</summary>
    <b><u><i>.length (EX: pets.length)</i></u></b>
</details>
</br>

**2. How can we use bracket notation to access the first element in our array and log it to the console?**

<details>
    <summary>Answer</summary>
    <b><u><i>console.log(pets[0]);</i></u></b>
</details>
</br>

**3. How can we use bracket nontation to access the last element in our array and log it to the console, regardless of how many elements we have inside of it?**
<details>
    <summary>Answer</summary>
    <u><b><i>console.log(pets[pets.length - 1]);</i></b></u>
</details>
</br>



### Use this Object to solve questions 4 to 6.

``` javascript
1. const games = [{
2.      name: "Final Fantasy X",
3.      costInDollars: 20.98,
4.      esrb: "T for Teen",
5.      platform: "PS2",
6.      onSale: true,
7.      }, {
8.      name: "Final Fantasy X-2",
9.      costInDollars: 18.08,
10.     esrb: "T for Teen",
11.     platform: "PS2",
12.     onSale: true,
13.     }
14. ]
```

**4. How can we use access the cost of "Final Fantasy X" and log it in the console?**
 

<details>
    <summary>Answer</summary>
    <b><u><i>console.log(games[0].costInDollars)</i></u></b>
</details>
</br>

**5. How can we use bracket notation ONLY to access the platform for Final Fantasy X-2?**

<details>
    <summary>Answer</summary>
    <b><u><i>games[1]["platform"]
    </i></u></b>
</details>
</br>

**6. What will be logged to the console if we ran the following code?**
```
console.log(games[0].onSale)
```
<details>
    <summary>Answer</summary>
    <b><u><i>True</i></u></b>
</details>
</br>