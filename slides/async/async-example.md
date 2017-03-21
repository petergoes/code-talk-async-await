```js
async function myFunction() {
    return 'Hello World';
};

console.log(myFunction()) // [object Promise]

myFunction()
  .then((value) => console.log(value)); // 'Hello World!'
```
