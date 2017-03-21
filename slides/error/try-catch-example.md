```js
async function myFunction() {
    try {
        const data = await getDataFromServer();
        const modifiedData = modifyData(data);
        return modifiedData;
    } catch (err) {
        throw new Error('Something went wrong');
    }
};

myFunction()
    .then(() => console.log('success'))
    .catch(err => console.log(err));
```
