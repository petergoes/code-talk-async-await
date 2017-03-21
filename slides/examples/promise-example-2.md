```js
async function myFunction() {
    const result = await Promise.all([prm1(), prm2()]);
    console.log(result); // ["Promise 1", "Promise 2"]
};

function prm1() {
  return new Promise(resolve => resolve('Promise 1'));
}

function prm2() {
  return new Promise(resolve => resolve('Promise 2'));
}

myFunction();
```
