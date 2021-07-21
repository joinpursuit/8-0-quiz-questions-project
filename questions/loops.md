Q: What is the purpose of a loop?

    A: Loops are a solution for completing repetitive tasks. Loop programs can simplify these tasks by repeating the same, or similar, code a number of times.  This number of times could be specified to a certain number, or the number of times could be dictated by a certain condition being met. 

Q: What is iteration?

    A: Often in an algorithm, a group of statements needs to be executed again and again until a certain condition is met. Iteration is the repeated execution of these groups of code statements in a program. 


Q: What are the steps to creating a loop?

    A: Generally with the for loop we create a variable, check a condition, and change the variable's value.
        ex: for (let num = 1; num < 10; num += 1) {
  console.log(num);
}
There are two semicolons. The part before the first semicolon defines a variable. The second part is a boolean expression that checks if the loop should continue. The last part updates the variable we created after every iteration. More formally, this is what each part is called:
for ([initialization]; [condition]; [increment / step]) {}

