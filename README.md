<!--This is Data Structure and Algorithm Folder -->
---
I have added all the core algorithm and Data sturcture here.  
### Recursion
<p>Print 1 to 10 numbers without Using Loop</p>

```javascript
function printNumber(num){
  console.log(num);
  if(num == 0) return 1;
  return printNumber(num-1);
}
printNumber(10);
```