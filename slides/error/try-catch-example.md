```js
async function myFunction() {
    try {
        const data = await getDataFromServer();
        return data;
    } catch (err) {
        throw new Error('Something went wrong');
    }
};

myFunction()
    .catch(err => console.log(err));
```
