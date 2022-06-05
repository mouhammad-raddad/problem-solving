```javascript
function getCount(str) {
  var vowelsCount = 0;
  let x=[...str];
  let y=x.map((x) => {if(x=='a'||x=='e'||x=='i'||x=='o'||x=='u')vowelsCount++})
  
  
  return vowelsCount;
}
```
