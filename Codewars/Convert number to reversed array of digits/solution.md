```javascript
function digitize(n) {
  let s=n.toString();
   let c= s.split("").reverse();
   let d= c.map((e)=> Number(e))
   return d;
}
```
