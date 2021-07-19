
# Looping Through Loops

**Q:** What is continue statement and when can it be used?
> A continue statment can be used to restart a while, do-while, for, or label statement. <br>
The syntax of the continue statemnt is <br>
`continue [label]`. <br>
For each loop, the `continue` label behaves differently but has the same outcome.
Continue does not end the execution of a loop. In a while loop, it looks back to the initial condlition. In a for loop, it looks to the increment expression.<br>
When a label is not included with the continue statement, it ends the iteration of the innermost enclosing while, do-while, or for statement cand continues executuin of the statements. When you have an label, the coninuation applies to the looping statement identified with the loop with the label.
---
**Q:** What are the different types of the for statemtents and how do they work?
> 1. **for statement** <br>
The syntax of the _for_ statement is  <br>
`for ([initialExpression]; [conditionExpression]; [incrementExpression])`. 
    * The first expressions: initialExpression is executed. The initial expressions begins the loop counters. The initial expressions often times declares variables. <br>* The second expression: conditionExpression is read my the conputer. If the the condition expression is true, the loop statement runs. If the condition expressions is false, the loop ends. If there isn't a condition expressions, then the condition is assumed to be true. <br> * If an incremenet expression exists, then it is executed by the computer. <br>
> 2. **for in statement** <br>
    The syntax for the _for in_ statement is <br>
    `for (variable in object)` <br>
     `statement`.  <br>
     *  iterates a specified variable over all the enumerable properties of an object. For each distinct property, <br>
> 3. **for of statement** <br>
    The syntax for the _for of_ statement is <br>
    `for (variable of object)` <br>
    `statement`. <br>
     The statement creates a loop going over iterable objects such as Array, Map, Set, arguments object and so on. It results in a custom iteration hook with statements  that will be executed for the value of each distinct property.
---
**Q:** What is an infinite loop and what are their effects? 
> Infinite loops are a sequence of instructions will continue endlessly, unless there is an intentional command to end it or a machine is unplugged. <br>
 Infinite loops can <br>1.  Use up all your processor time so your system becomes unresponsive. <br> 2. Allocate some memory in every iteration and not release it, so you will eventually run out of RAM and your system, again, becomes very slow. <br> 3. Write to your storage disk until it is full. 