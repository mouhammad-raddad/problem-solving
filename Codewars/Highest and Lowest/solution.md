```javascript
function highAndLow(numbers){
  let a = numbers.split(" ");
  let max=-9999,min=9999;
  a.forEach((e) => {
      if(Number(e) > max && e!== "")max =Number(e);
      if(Number(e) < min && e!== "")min = Number(e);})
  let b=max.toString()+" "+min.toString();
  return b;
}
```
