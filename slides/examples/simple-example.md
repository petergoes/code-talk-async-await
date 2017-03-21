```js
async function myFunction() {
    const fromAsync = await returnsAsync();

    console.log(fromAsync); // Async!
};

async function returnsAsync() {
    return 'Async!';
}

myFunction();
```
