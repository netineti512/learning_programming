# 1. JavaScriptの概要

<details><summary>ソースコード</summary><div>
  
  ```sample.js
  console.log("Hello World");
  ```
  
</div></details>

# 2.

# 8. 関数

<details><summary>ソースコード</summary><div>
  
```sample.js
function printprops(o) {
    for (let p in o) {
        console.log(`${p}: ${o[p]}`);
    }
}

function distance(x1, y1, x2, y2) {
    let dx = x2 - x1;
    let dy = y2 - y1;
    return Math.sqrt(dx * dx + dy * dy);
}

function factorial(x) {
    if (x <= 1) return 1;
    console.log("x=", x)
    return x * factorial(x - 1);
}

printprops("jibjhbd")

a = distance(1, 2, 3, 4)
console.log("a=", a)

b = factorial(100);
console.log("b=", b)  
```
  
</div></details>
