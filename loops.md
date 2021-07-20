# Loops

* ### Explain loops (for non-coders != dummies).
  
  *  If you were to sing the nursery rhyme "Five little monkeys jumping on the bed" but instead of five monkeys if there were 100 monkeys, the first line would start as "100 little monkeys jumping on the bed" till we came to "1 little monkey jumping on the bed". If we had to wirte the nursery rhyme in code using loops we could write that using just one sentence, 100 little monkeys jumping on the bed then subtract 1 each time till there are no more monkeys left. Loops allows us to repeat the code till it reaches the end value. 

     Below is an example of "100 little fish swimming in the sea" (used fish instead of monkeys as it is the same, singular or plural) 

     ```JS
     let fish = 100;
     while (fish > 0) {
     console.log(`${fish} swimming in the sea ...`);
     fish--;
     }
     ```




* ### The loop below will keep iterating, is there a way to end the loop?

    ```js 
    let num = 1;
    while (num <= 10) {
    console.log("the number is: " + num);
    }
    ```

  * If the condition for a loop is true it can keep running until the condition is false. So, as long as the condition is true a loop can keep iterating forever, to stop the loop from iterating we can either have a condition where there is a limit where once it reaches the limit it will stop or add __'break;'__. The loop above num is 1 and the condition instructs as long as num is 1 and less than or equal to 10 to print  ("the number is: " +num) so it will keep printing "the number is 1". To end the loop we can add __'break;'__

    ```js
    let num = 1;
    while (num <= 10) {
    console.log("the number is: " + num);
    break;
    }
    ```
    


* Why would we use a __for__ loop instead of a __while__ loop?

  * A __for__ loop acts just like a __while__ loop the only difference between the two loops, a __for__ loops is shorter. In a __for__ loop we have a variable, a condition or statement that needs to be met or be true, and the updated variable status after an iteration in a parenthesis with two semicolons. 
  
    Below is an example of a __for__ loop that is equivalent to the __while__ loop used earlier -

     ``` js
     for (let num = 1; num <= 10; num)
     console.log("the number is:" + num)
     ```
