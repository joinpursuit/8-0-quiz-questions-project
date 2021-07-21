# Topic: Functions

**Question One** What is a functions role in JavaScript?
>Ans: A function performs a task through a series of code.Everytime a function is called, the fucntion will fun the task that it was designed to do. 

**Question Two** What is a barebones way to write a function?
>Ans: function name() {} is the barebones way to write a functions.

**Question Three** When it comes to functions, what are "arguments"?
>Ans: An argument is the "case" that gets passed when the user calls it.

**Bonus:** What is the difference between a parameter and an argument? Identify them.

    ```js
    const name = "Poppy";
    const age = 4;

    function printNameAndAge(animalName, animalAge) {
        console.log(`${name} is ${age} years old.`);
    }

    printNameAndAge(name, age)
    ```
>Ans: A parameter is what is inside the function and describes "cases" with that functions definitions. Parameters and arguments do not need to have the same name.