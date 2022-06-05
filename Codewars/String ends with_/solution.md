```javascript
function solution(str, ending){
  a=str.split("");
  b=ending.split("");
  let flag=true;
  for(let i=b.length-1,j=a.length-1;i>=0;i--,j--){
    if(b[i]===a[j]||b[i]==="")
      flag=true;
    else 
      return false;
  }
  return flag;
}
```
