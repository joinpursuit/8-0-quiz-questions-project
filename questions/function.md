**Q1:**  What is the difference between a parameter and an argument?
    
<details>
<summary>Answer</summary>

>An argument is the value you give to a parameter and a parameter is a placeholder or special variable. 
</details>

<br>

**Q2:** Imagine that you wrote the following pseudocode.  

`// We are declaring a const variable called actual and we are assigning it the evaluated result of invoking "name formatter" passing in the argument name`

Your task now is to convert this pseudocode to code.

<details>
<summary>Answer</summary>

>const actual = nameFormatter(name)
</details>

<br>

**Q3:** What will happen when you invoke the function called test and pass the argument "Hello".? 

```javascript
function test(string) {
	return string
}

test("Hello")
```

<details>
<summary>Answer</summary>

>When the function called test is invoked and passes the argument "Hello" it will return the string "Hello" but we will not see it logged in the console. 
</details>