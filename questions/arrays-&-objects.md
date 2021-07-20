## Q: What is an *array* and an *object*?

> An _array_ is a single variable that is used to store different elements. An example is;

```javascript
Teams = [true, 'Yankees', 50]
```

There are three different data type elements within this array.

> An object is a standalone entity, with properties and type. An example is;

```javascript
const myCar = {
    make: 'Ford',
    model: 'Mustang',
    year: 1969
};
```

> *myCar* is the object, *make/model/year* are the properties and the values given contain different data types withing the object.

## Q: Can *objects* be stored in an *array*? If so, provide examples.

> Yes, objects can be stored within an array.

```javascript
participants = [
  runner1 = {
    position: 1,
    name: 'Bowsner',
    age: 32,
 },
  runner2 = {
    position: 2,
    name: 'Rockland',
    age: 30,
 }
]
```
> In the above example there are two objects with properties ans types within an array.

## What are the differences between *arrays* and *objects*?

> *Arrays* are *objects* in javascript. They are used to store data in an ordered collection that can be accessed using a numerical index.

> *Objects* are used to represent a ‘Thing’. This could be anything like cars, plants, person etc.