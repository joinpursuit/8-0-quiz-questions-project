Arrays
***Q*** Look at the array below. At what index is “V12 Vanquish”?

```js 
function logAstons () {
let astonMartins = [“V12 Vanquish”, “Vantage”, “Virage” “DB9”, “DB11”];
console.log(astonMartins[)
}
```

>Array indexes start at 0. So “V12 Vanquish” is at array position 0. This is very important to remember!

***Q**** What would happen in the code presented below? 

```js

const porshes = ["Boxter", "Panamera", "Carrera GT", 911 + " Turbo"];
porshes[10] = "918 Spyder";
console.log(porshes);

```

>The array will be logged added the new Porsche model, 918 Spyder. The spaces between the 3rd and 10th indexes will be empty. 

***Q***
Ferrari is updating it’s model line. It’s line consists of the 812 Superfast, 296 GTB, F8 Tributo. A new model the Roma is being introduced, replacing the F8 Tribute how can we reflect that change in the model line which the array below affects.

```js
const ferraris = [812 + " Superfast", "Panamera", "F " + 8 +" 
[image:6258A77B-93D9-4FFF-A3DB-FFA989448AC8-2219-0000174C7D45F5F9/Screen Shot 2021-07-20 at 10.12.57 PM.png]
Tributo", "Lusso"];
ferraris[2] = "Roma";
console.log(ferraris);
```

We can use “bracket notation” to update the model from “F8 Tributo” to Roma. Remember, because indexes start at 0, the update needs to happen at the 3rd index. 
