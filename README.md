# 

```javascript
console.assert(o instanceof Arithmetical, true);
console.assert(typeof Arithmetical.prototype.times, 'function');
console.assert(o.times(10, 2), 20);
console.assert(o.divide(10, 2)(), 5);
console.assert(o.add(10, 2).equals(), 12);
console.assert(o.subtract({ left: 10, right: 2 }).equals(), 8);
```
