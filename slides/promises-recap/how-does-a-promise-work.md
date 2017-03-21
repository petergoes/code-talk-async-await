```js
const promise = new Promise((resolve, reject) => {

    setTimeout(() => {
        resolve('Time!');
    }, 2000);

});

promise
    .then(value => console.log(value)); // Time!

console.log(promise); // [object Promise]

```
