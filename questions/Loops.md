**Q:** What are `loops` used for?

> <details> Loops are used for repeating a task for a number of times until the breaking condition for the loop is met. If the breaking condition is never met, then we will have produced an infinite loop so it is best to always ensure that the breaking condition will eventually be met. </details>

**Q:** What are the 3 things that every `loop` has?

> <details> Every loop has an initial value, a breaking condition, and an update expression. Our update expression is what gets us closer to our breaking condition in order for us to naturally break out of your for loop. </details> 

**Q:** What approach could I take if I wanted to get the count of characters in a string using a loop?

> <details> One of the best ways to accomplish this task is to create a cache object which will be initialized to an empty object literal, afterwards iterate through the string utilizing a for loop and then at each index position, create a conditional statement which would check to see if the object at current element exists as a property inside of the object and if it does, increment the count by 1 otherwise create the property in the object and assign it the value of 1 starting off. </details>