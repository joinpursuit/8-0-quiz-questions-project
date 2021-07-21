# Arrays & Functions

**Q:** What is the interaction between `Arrays & Functions` ?

> Functions are important when it comes to writing reuseable code, as well as writing code that is triggered when an event occurs. Arrays are a way of storing data that can be called upon, commonly by and/or within functions.

---

**Q:** What will be the outcome of the following code?

```js
const bP = ['🍌','🎉'];
const partyTime = ['🎂'];

function bananaParty (bP) 
{
  if (partyTime === '🎂' )
  {
   return `It's ${bP[0]} ${bP[1]}  time!`;
  }
};

bananaParty(bP);
```

> Nothing will be returned. <br> This is due to `partyTime` being an array <br> and `'🎂'` being `index position [0]` which is not called upon and therefore returns `false` for the `if` statement. <br> We need to change it to <br> `if (partyTime[0] === '🎂' )` <br> in order for it to work.

---

**Q:** What will be the outcome of the following code?

```js
const bP = ['🍌','🎉' ] ;
let bananaParty = (bP) =>
{
    let bPpT = bP.push({partyTime: '🎂'});
    if (bP[2].partyTime === '🎂' )
  {
    return `It's ${bP[0]} ${bP[1]} time` + ' Greg!';
  }
  else {return `Grrrrrrrrrrr`}
};

bananaParty(bP);
```

> It's 🍌 🎉 time Greg! <br>
Will be what is returned.<br>
Although the object is pushed into the array it 
still has an <br> `index position of [2]`. <br> Since `'🎂'` is in that index position with the key <br> `partyTime: ` represented by `.partyTime` <br> We get the result `true` which triggers the return. <br>
`=>` is an arrow function expression that treats ( ) before it as a parameter and everything between { } as an expression.

---

**Q:** What will be the outcome of the following code?

```js
const bP = [
  { emojis: [{ banana: "🍌", party: "🎉", partyTime: "🎂" }] },
  {
    time: [
      { estart: "18:30", estEnd: "23:30", pdstart: "16:30", pdtEnd: "21:30" },
      {
        timeZone: function (time) {
          var diff = time.split(":");
          return parseInt(diff[0]) * 60 + parseInt(diff[1]);
        },
      },
    ],
  },
];

const startEnd = {
  tZ: bP[1].time[1].timeZone,
  estart: bP[1].time[0].estart,

  pdstart: bP[1].time[0].pdstart,

  estEnd: bP[1].time[0].estEnd,

  pdtEnd: bP[1].time[0].pdtEnd,
};

const tZsE = {
  timezoneStart: startEnd.tZ(startEnd.estart) - startEnd.tZ(startEnd.pdstart),
  timezoneEnd: startEnd.tZ(startEnd.estEnd) - startEnd.tZ(startEnd.pdtEnd),
  tZeS: startEnd.tZ(startEnd.estart),
  tZeE: startEnd.tZ(startEnd.estEnd),
  tZpS: startEnd.tZ(startEnd.pdstart),
  tZpE: startEnd.tZ(startEnd.pdtEnd),
};

let bananaParty = (currentTime, tZg) => {
  let tZgVal = startEnd.tZ(currentTime);
  if (
    tZg == "est" &&
    tZgVal - tZsE.tZpS > tZsE.timezoneStart &&
    tZgVal - tZsE.tZpE < tZsE.timezoneEnd
  ) {
    if (bP[0].emojis[0].partyTime === "🎂") {
      return `It's ${bP[0].emojis[0].banana} ${bP[0].emojis[0].party} time Greg!`;
    }
  } else if (
    tZg == "pdt" &&
    tZsE.tZeS - tZgVal > tZsE.timezoneStart &&
    tZsE.tZsE - tZgVal < tZsE.timezoneEnd
  ) {
    if (bP[0].emojis[0].partyTime === "🎂") {
      return (
        `It's ${bP[0].emojis[0].banana} ${bP[0].emojis[0].party} time` +
        " Greg!"
      );
    }
  } else {
    return `Grrrrrrrrrr`;
  }
};

bananaParty("10:00", "est");
```
> `Grrrrrrrrrr` <br>
will be returned. <br>
This is due to `10:00` being run through the function within the `bP` array via <br> `let tZgVal = startEnd.tZ(currentTime)` <br>
`startEnd.tZ` <br> which points to <br>`bP[1].time[1].timeZone`. <br>
The function is <br>
`timeZone: function (time) {
          var diff = time.split(":");
          return parseInt(diff[0]) * 60 + parseInt(diff[1]);`
<br><br> The time `10:00` is split into an array of `[10,00]`, the hours side `10` is multiplied by 60 and added to the other `00`. <br><br>
The value returned is `600` which then is run through <br> `if (
    tZg == "est" &&
    tZgVal - tZsE.tZpS > tZsE.timezoneStart &&
    tZgVal - tZsE.tZpE < tZsE.timezoneEnd
  )` <br> because `est` was the parameter for `tZg`. <br><br>
  `tZsE.tZpS` <br>(represents `pdstart` from the array `bP` going through the same `timeZone` function `tZgVal` went through) <br>which comes out to the value of `990` is subtracted from `tZgVal`<br> which then is compared to the time zone difference.<br>
  The difference in time between EST and PDT is two hours <br> or `120` since it's run through the same `timeZone` function. <br>
  `600` - `990` is `-330` which is less than `120`. This makes `tZgVal - tZsE.tZpS > tZsE.timezoneStart` = `false` and the `else` statement is triggered instead.
