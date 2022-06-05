```javascript
function well(x){
  let counter = 0;
  for(let i=0;i<x.length;i++){
    if(x[i] === 'good')
      counter++;
  }
  if(counter === 1 || counter === 2)
    return 'Publish!';
  else if(counter >= 2)
    return 'I smell a series!';
  else return 'Fail!';
  
}
```
