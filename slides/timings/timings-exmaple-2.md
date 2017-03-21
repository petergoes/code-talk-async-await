```js
async function () {
    const value1Promise = takes2Seconds();
    const value2Promise = takes4Seconds();

    const value1 = await value1Promise;
    const value2 = await value2Promise;

    console.log(`value1: ${value1}`);
    console.log(`value2: ${value2}`);
}
```
