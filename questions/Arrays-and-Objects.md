# Arrays and Objects
**Q1:** When trying to store values in a single variable, what object class should be used?
> An `Array` would be used to store multiple values in one variable. Can contain any data type. `Arrays` are created with `[]` square brackets with the values within them and commas separating the values.
```js
let varName = ["val1", "val2", ..., "valN"]
// can also span multiple lines.
let vaeName = [
    "val1",
    "val2",
    "val3",
]
```
---
**Q2:** What would be used to give each key a value in a variable?
>`Objects` are used to give a value to keys. Any data type can be used as the value. `Objects` use `{}` curly braces with the keys and values within them.
```js
let book = {
    name: 'Animal Farm',
    author: 'George Orwell',
    Pages: 141,
    published: undefined
}
```
---
**Q3:** How can these two objects be used together?
>`Objects` can be within `Arrays` to creat multiple values with elements.
```js
const books = [
    {
        name: 'Animal Farm',
        author: 'George Orwell',
        Pages: 141,
    },
    {
        name: 'Lord of the Flies',
        author: 'William Golding',
        Pages: 208,
    },
    {
        name: 'Brave New World',
        author: 'Aldous Huxley',
        Pages: 259,
    }
]
```