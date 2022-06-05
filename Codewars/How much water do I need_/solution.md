```javascript
function howMuchWater(water, load, clothes){
  // Insert your brilliant code here
  if(clothes >= 2*load)
    return 'Too much clothes';
  else if(clothes < load)
    return 'Not enough clothes';
  else 
    return +(water * 1.1 ** (clothes-load)).toFixed(2);
  
}
```
