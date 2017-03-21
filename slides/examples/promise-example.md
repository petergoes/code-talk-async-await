```js
async function myFunction() {
    const fromPromise = await returnsPromise();

    console.log(fromPromise); // Promise!
};

function returnsPromise() {
  return new Promise(resolve => {
    resolve('Promise!');
  });
}

myFunction();
```
