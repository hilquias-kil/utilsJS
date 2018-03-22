# utilsJS

## Immutable change

change a item in the array by index, and return new array.

```js
const insertByIndex = (state, newItem, insertAt) =>{
    let arr = state.slice()
    arr[insertAt] = newItem;
    return arr;
}
```

## Links

- [You might not need lodash](https://youmightnotneed.com/lodash/) | utils plain js
