```javascript
function multiTable(number) {
  let str="";
  for(let i=1;i<=10;i++){
    str+=`${i} * ${number} = ${i*number}\n`;
  }
  return str.slice(0,-1);
}

multiTable(5);
```
