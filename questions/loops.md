## LOOPS

**Q** What will happen if we run the code below? and how do we fix it? 
``` js
let num = 1;
while(num < = 5){
    console.log('The number is: '+ num);
    }
```
> This will create an infinite loop. Since num will always be less than 5, the loop will always console log since the while loop requirements are being met. 

> To fix this , we should add ```num += 1;``` after the ```console.log```. This will have num increase by one after every loop. once num reaches 5, the loop will stop.

---

**Q** Explain the code below 
``` js
for (let num = 1; num < 10; num += 1){
    console.log(num);
}
```
> ```num``` will start at 1. The loop limit is 9 and after each loop, add 1 to ```num```.

> Until ```num``` is ```>=10``` , the code will ```console.log(num)```

---

**Q** Define Break and Continue is loops

> Break will stop a loop when a certain condition you set is met. 

> Continue will skip over/ignore a ceratin condition you set. 