```javascript
function countPositivesSumNegatives(input) {
  let count=0;
  let sum=0;
  let arr=[];
  if(input!=null){
  for(let i=0;i<input.length;i++){
    if(input[i]<=0){
      sum+=input[i];
    }
    else{
      count++
    }
    arr[0]=count;
    arr[1]=sum;
    
  }
  return arr;}
  return [];
  
    
}
```
