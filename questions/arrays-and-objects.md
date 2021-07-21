# Arrays and Objects

**Q:** How do you add or change a property in an object?

> When given an object you can change a key value pair by declaring one that already exists again or add a key value pair by delcaring one that does not already exist. If you already have an object declared such as

```js 
let obj = {
    when: 'today',
    where: 'here',
    who: 'you',
}
```

>Then you can change the `who` value by declaring it again outside of the object, like so

```js
obj.who = 'me'
```

>You can even add a key value pair like this:

```js
obj.what = 'surprise'
```
---

**Q:** What change will made to the array in the following code?

```js
let arr = ['first', 'second', 'third',];
arr.push('HA');
```

> The array will have 'HA' added to the end. It will turn out like this:

```js
arr = ['first', 'second', 'third','HA']
```

---

**Q:** How, in this object, would you access the Andrew's hobby?

```js
let arr = [
    {
    name: {
      firstName: 'Andrew',
      middleName: 'Denis',
      lastName: 'Johnson',
    },
    life: {
        hobby: 'guitar',
        job: 'teacher',
    }
    },
    {
    name: {
      firstName: 'Nicole',
      middleName: 'Anna',
      lastName: 'Williams',
    },
    life: {
        hobby: 'embroidery',
        job: 'accountant',
    }
    },
]
```

> To access Andrew's hobby you would use the following code:

```js
arr[0].life.hobby
```
---

**Q:** What do you use arrays and objects for?

> You use arrays and objects to store data to call upon later and throughout your code.

---
