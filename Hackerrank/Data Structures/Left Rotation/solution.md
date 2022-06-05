```javascript
function rotateLeft(d, arr) {
  while (d) {
    arr.push(arr.shift());
    d--;
  }
  return arr;
}
```
