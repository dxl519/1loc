---
title: Get variable type
category: Function
---

**JavaScript version**

```js
const trueTypeOf = (obj) => Object.prototype.toString.call(obj).slice(8, -1).toLowerCase();
```

**Examples**

```js
let a = 1;
let b = '111';
let c = true;
console.log(trueTypeOf(a)); //number
console.log(trueTypeOf(b)); //string
console.log(trueTypeOf(c)); //boolean
```
