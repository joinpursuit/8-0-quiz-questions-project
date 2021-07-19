# Loops

**Q:** Why is `for of` loop preferred over a `for i` loop for iterating through arrays?

> A: The `for of` is built specifically to work well with arrays,  
because it can go through each element without conditional and an increment expression. It is easy and convinient.

---

**Q:** How are loops different than conditional statements?

> A: Loop code blocks stop executing once a certain condition is met, loops can also execute code as many time as possible.  
Conditional statements execute if and only if a certain condtional is true or truthy, and is usually executes only once.

---

**Q:** What is "off-by-one-error"? And how to avoid it?

> A: When working with arrays, and `i` in the for loop is set to start at 1st index instead of zero index.  
Make sure to remember that the first element has the index of zero, and start there if you want to start from the first element.

---
