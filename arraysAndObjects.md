# Array & Objects Questions

**Q1.** Name three data types that are stored in an `Array`?

> The answer is `Strings,` `Numbers,` and `Objects.` An `Array` is a particular type of variable. It stores one value or a list of values. 

---

**Q2.** Name two ways you can access the properties of an `Object`?

> Two ways to access an `Object's` properties are `Dot Property` and `Square Bracket Property.` 

```JavaScript 

// Dot property 
const hero = {
  name: 'The Hulk'
};

hero.name; // => 'The Hulk'

```

```JavaScript

// Square brackets property:
const property = 'name';
const hero = {
  name: 'Batman'
};

hero['name'];   // => 'Batman'

```

---


**Q3.** In what data structure does the order of properties matter?

> The answer is `Arrays.` In an `Object,` the order in which the properties appear is not essential. However, in an `Array,` the index numbers dictate the order of the properties. 