# Functions

* ### How do you declare a function?
  
  * To declare a function first we have to write function and give the function a name followed by a parenthesis, and add open and closing curly brackets. The statement in between the curly brackets is the code that will be executed each time the function is called.
    ```js 
      function introduction(){
      let intro = "Hello!"
      return(intro);
      }

    ```

* ### The above function will not execute. Why and how can it be executed?

  * For a function to execute it has to be called or invoked, to run the function above we have to invoke the function. The following code will invoke or call the function that will store the value for intro as __"Hello!"__. 


    ```js
  
    introduction();

    ```

* ### Will declaring the function print out "Hello!"? Why and how can it be printed? 

  * Declaring a function with a return and calling a function does not automatically print out the value for intro. Calling the function with a return simply stores the value for intro as __"Hello!"__. To print out __"Hello!"__ the function has to be console.logged.

    ```js

    console.log(introduction());

    ```
