### **Q:** How could you navigate to 'here' with the obj variable?

```js
let obj = {
  a:[1,2,3,4,5,6],
  b:[4,5,6],
  c:[7,8,9],
}
let ins = {
  abc:[123, 'here'],
  def:[4,5,6]
}
obj.c.push(ins)
```

> The answer is **obj.c[3].abc[1]** because you see that this new object is inserted into the first 'obj' you would go through the first part with **obj.c** and then **[3]** because the 'ins' was pushed to the end of c's array.  Followed by **.abc[1]** to access the object and the 2nd item in the array.  This could be an interesting question because it looks confusing and should let people figure out or at least think about how to navigate around while also learning that you can just add things into objects/arrays.

### **Q:** Is there a difference between the values in a and b?

```js
let x = [1,2,3,4,5]
let a = x[0]
let b = x.shift()
```
> The answer is 'no' a and b both contain 1, however there is a difference in what occurs to the initial array.  Question could also be modified to be yes by shifting the bottom line up. Or could even use the same code and ask a question about whether the overall results are the same. This could be a way to further enforce the difference of how both can view the same item, but one affects ths inital array.

### **Q:** What does y look like after running the code below?

```js
let x = [0,1,2,3,{random: 'object'},4,5,6,7]
let y = x.slice(3)
```

> The answer should be [3,{random: 'object'},4,5,6,7]. As a way to introcude/reinforce the slice method. Also may resolve any confusion on whether slice splits before or after the declared index.

