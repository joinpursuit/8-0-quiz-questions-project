# Arrays and Objects

***Question 1:***
How would you show the dot notation and bracket notation of this example:

```js
let pursuitFellow = {name: 'Trevor'}
```

```js
pursuitFellow.name

pursuitFellow['name']
```
>Answer: In the above example, `pursuitFellow` is a variable with a key represented by `name` and a value of `Trevor`. The above answer shows with dot notation the object `pursuitFellow` followed by a dot `.` and the property `name`.  The bracket notation shows the object `pursuitFellow` surrounding the property `'name'`  with square brackets `[]` and quotes `''`.
---

***Question 2:***
How would you properly arrange these words relating to the object flower:

```js
rose, genus, family, rosa, rosaceae, type.
```
>Answer: You would have to format them as `{key: value}` or `properties` of the object.  In this scenario, the object `flower` has the above `properites` and they will be formatted in this way:

```js
{
    type: 'rose',
    genus: 'rosa',
    family: 'rosaceae'
}
```
The properties are written in the `{key: value}` format, with the value followed by a comma afterwards, the strings in quotes and the last value without a comma at the end with everything surrounded by curly braces in the beginning and end of the code.

***Question 3:***
What is the difference between the array indexes and the array length?

```js
const myKids = ['TJ', 'Amber', 'Madison', 'Blake'];
```
>Answer: The index of the array refers to its placement in the `[]` of the array and its count starts at 0. So if we wanted print index `[3]` of this array:
```js
const myKid = myKids[3];
console.log(myKid);
```
It would print  `'Blake'` in the terminal since if the count starts at index `[0]`, that would be index `[3]` in that array. The array length refers to the amount of elements in the array surrounded by `[]`. In the above example, the array length is 4 because there is 4 total elements in that array. 