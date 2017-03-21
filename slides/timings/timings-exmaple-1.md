##  Consider this

```js
async function () {
    const value1 = await takes2Seconds();
    const value2 = await takes4Seconds();

    console.log(`value1: ${value1}`);
    console.log(`value2: ${value2}`);
}
```
