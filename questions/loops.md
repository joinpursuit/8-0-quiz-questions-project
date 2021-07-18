# Loops

***Question 1:***
The code in the below example looks good, but when running it with tests it didn't pass.  What happened and what can be done to pass this test?

```js
function logNamesOfOutOfStockProducts(products) {
  for(products of products) { 
     if (product.inStock === false) {
     console.log(product.name);
    }
  }
}
```
>Answer: In the `for...of` statement, `products` is the element and array which essentially makes parameter `undefined`. A simple removal of the letter `s` in the first `products` to `product` will make the computer read it as a different element and allow the test to pass or naming it something completely different.

**Correct Codes**
```js
function logNamesOfOutOfStockProducts(products) {
  for(product of products) { 
     if (product.inStock === false) {
     console.log(product.name);
    }
  }
}

function logNamesOfOutOfStockProducts(products) {
  for(element of products) { 
     if (product.inStock === false) {
     console.log(product.name);
    }
  }
}
```
