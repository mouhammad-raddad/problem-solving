```javascript
function getAverage(marks){
  let avg=0;
  let c=0;
  let sum=0;
  for(let i=0;i<marks.length;i++){
    sum+=marks[i];
    c++;
}
avg=sum/c;
return Math.floor(avg);
}
```
