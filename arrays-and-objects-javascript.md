# Arrays and Objects

**Question One** What `data type` would both Arrays and Objects be considered?
>Ans: Both are considered to be `reference types`. Reference types point not to the value of an element but refrences the `address` or `place in memory` for which it was stored. 

**Question Two** What are the properties called in objects?
>Ans: The properties in objects are referred to as `key-value pairs`
```js
    key.value or key["value"]
``` 

**Question 3** How would one access the key value: `"Fresh Coconut Pancakes"`?  
//Address: 1600 Amsterdam Ave, New York, NY 10031

```js
let restaurants = [
      {
        name: "Fumo",
        food: [
          "SPAGHETTI CARBONARA",
          "RIGATONI SALSICCIA",
          "Scythe",
          "ARUGULA",
          "FRIED CALAMARI",
        ],
        address: {
          street: "1600 Amsterdam Ave",
          city: "Manhattan",
          state: "NY",
          zip: 10031,
        },
      },
      {
        name: "Clinton St. Baking Company & Restaurant",
        food: [
            "Maple Bourbon Pecan Pancakes", 
            "Fresh Coconut Pancakes", 
            "7 Wonders", 
            "Blueberry Yuzu Pancake"
            ],
        address: {
          street: "4 Clinton St.",
          city: "New York",
          state: "NY",
          zip: 10002,
        },
      },
    ];
```

>Ans: console.log(restaurants[1].food[1])