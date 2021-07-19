## Arrays & Objects Questions and Answers  
<p>&nbsp;</p>

## ARRAYS QUESTIONS....

<p>&nbsp;</p>

## Q 1. Name two ways to dynamically add the value “bar” to the array “foo”
```js
foo.push("bar")
 foo[foo.length] = "bar";

```
>**Answer** explained in the example above

<p>&nbsp;</p>

## Q 2. Of what JavaScript type is an Array?
>**Answer**: object

<p>&nbsp;</p>
<p>&nbsp;</p>

## Q 3. If the array “foo” has a length of 10, what is the index of the last element in the array?
>**Answer**: 9  
**Hint:** JavaScript Arrays are zero-based

<p>&nbsp;</p>
<p>&nbsp;</p>

## OBJECTS QUESTIONS....

<p>&nbsp;</p>

## Q 1. What Is Javascript Objects?  
>**Answer:** JavaScript is an Object Oriented Programming (OOP) language. A programming language can be called object-oriented if it provides four basic capabilities to developers −

- Encapsulation − the capability to store related information, whether data or methods, together in an object.
- Aggregation − the capability to store one object inside another object.
- Inheritance − the capability of a class to rely upon another class (or number of classes) for some of its properties and methods.
- Polymorphism − the capability to write one function or method that works in a variety of different ways.  

Objects are composed of attributes. If an attribute contains a function, it is considered to be a method of the object, otherwise the attribute is considered a property.

<p>&nbsp;</p>

## Q 2. What Are The Javascript Native Objects?  
>**Answer:** JavaScript has several built-in or native objects. These objects are accessible anywhere in your program and will work the same way in any browser running in any operating system.

Here is the list of all important JavaScript Native Objects −

- JavaScript Number Object
- JavaScript Boolean Object
- JavaScript String Object
- JavaScript Array Object
- JavaScript Date Object
- JavaScript Math Object
- JavaScript RegExp Object

<p>&nbsp;</p>

## Q 3. What Is Object Methods?
>**Answer:**

- Methods are the functions that let the object do something or let something be done to it. There is a small difference between a function and a method – at a function is a standalone unit of statements and a method is attached to an object and can be referenced by the this keyword.

Methods are useful for everything from displaying the contents of the object to the screen to performing complex mathematical operations on a group of local properties and parameters.

- For example − Following is a simple example to show how to use the write() method of document object to write any content on the document.
```js
document.write("This is test");
```