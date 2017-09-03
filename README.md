# js冒泡排序jsBubbleSort

demo code:

```
   var numArr = [5,7,9,0,5,3,1,4,6,111,23,1,8767,32,24567,8];
        for(var j = 0;j < numArr.length-1;j++){
            for(var i = 0;i < numArr.length-1;i++){
                if(numArr[i] > numArr[i+1]){
                    var num = numArr[i+1];
                    numArr[i+1] = numArr[i];
                    numArr[i] = num;
                }
            }
        }
        console.log(numArr);
```

