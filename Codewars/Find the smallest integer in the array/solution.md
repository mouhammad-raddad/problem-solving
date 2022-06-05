```javascript
class SmallestIntegerFinder {
  findSmallestInt(args) {
    let min = 9965269;
    args.map(x=>{if(x<min)min=x;})
    return min;
  }
}
```
