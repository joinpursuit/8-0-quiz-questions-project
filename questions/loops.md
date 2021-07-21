# Topic: Loops

**Question 1**  What does the following code return and what is is called?

        ```js
      function sumAllNumber(numbers) {
        let sumAll = 0;
            for(let i=0; numbers.length; i++) {
                sumAll += numbers[i]
            }
        return sumAll;
            }
        ```
 >Ans: The following code returns an infinite loop because `numbers.length` is not being compared to an `index` at the moment. While running this loop the computer will constantly ask "is numbers.length true?". Which is infact always true, and continues to loop infinitley. 

**Question 2** The following are two scenarios. State why the loop is appropriate for the scenario. 
Scenario 1: The water cycle

```js
//WATER CYCLE
 while (sun===true){
     evaporation();
     condensation();
     precipitation();
 }  
```
Scenario 2: Stacey is listening to music. How many times will it take to get tired of "Old Town Road -Lil Nas X". While she likes this song she will dance.

```js
let staceyLikeSong = "true"; //number of times stacey likes this song
for (let i=0; i < staceyLikesSong.length; i++>) {
    let dance = "true";
}
```
>Ans: Scenario 1 is using a `While` loop because while there is a sun present the water cycle will continue to occur. Scenario 2 is using a for loop, because we are looping through the number of times that stacey enjoys the song. 

**Question 3** What is the main difference between a `while` and a `for` loop?

>Ans: The `for` loop is used when you know how many times the loop would be required to run. 
> The while loop will continue to run `WHILE` the condition is satisfied, without knowledge of number of times needed to be iterated. 