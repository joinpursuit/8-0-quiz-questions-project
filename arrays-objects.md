# Arrays & Objects

* ### Define arrays and objects (for non-coders != dummies).
  
  * Objects is used to describe a variable with properties that consist of key and value pairs in a curly bracket. A function can also be performed in an object and that is a method. 

    Arrays are also a type of object, but it is a list of elemnets and just like multiple items in a shopping list is numbered, the elemnets in an array are indexed and start at 0 inside square brackets.
    
    An object is used to describe an item and an array is a list of items.

   Below is an example of a simple object with a function performed inside the object -
    ```js 
    let car = {
        make: 'Mini',
        model : 'Hatch',
        year : '2020',
        color : 'yellow',
      carInfo : function(){
    console.log(`I like the ${car.year} ${car.make} ${car.model} in ${car.color}!`);
      }
    }
     car.carInfo();  //> this will print 'I like the 2020 Mini Hatch in yellow!' 
    ```
    Below is an example of a simple array - 
    ```js
     let colors = ["red", "yellow", "green", "blue"];
 
    console.log(colors[0]); //> this will print 'red'

    console.log(colors[1]); //> this will print 'yellow'
     
    ```

* ### How can we access the last elemnet of an array ?

  * We can easily access the elemnets of an array by using the index number but what if the array consists of 500 elements. The most effeicient way to access the last element of an array we can use **_index array.length - 1_** 
  
  ```js
  let countries = ["Italy", "Vietnam", "Greece", "Thailand", "China", "Switzerland"];

  console.log(countries[countries.length-1]); //> this will print 'Switzerland'

  ```


* Examples of a few common methods (for non-coders != dummies).

  * Below are a few common methods to add or remove elements from the beginning or an end of an array.
  
  **push()** - is used to add an element to the end of an array
  ```js
  let apples = ['Honeycrisp']
  apples.push('Pink Lady') //> will update the array ['Honeycrisp','Pink Lady']
  apples.push('Red Delicious','Hidden Rose') //> will update the array ['Honeycrisp','Pink Lady','Red Delicious','Hidden Rose']
  ```
  **pop()** is used to remove an element from the end of an array
  ```js
   let states = ['Colorado', 'California', 'New mexico', 'Arizona', 'Utah', 'Vermont']
   states.pop(); //> will update the array ['Colorado', 'California', 'New mexico', 'Arizona', 'Utah']
  ```
  **unshift()** is used to add an to the beginning of an array
  ```js
  let states = ['Colorado', 'California', 'New mexico', 'Arizona']
  states.unshift('Utah') //> will update the array ['Utah','Colorado','California','New mexico','Arizona' ]
  ``` 
  **shift()** is used to remove an item from the beginning of an array
  ```js
  let apples = ['Honeycrisp','Red Delicious','Hidden Rose']
  apples.shift() //> will update the array ['Red Delicious','Hidden Rose]
  ```


