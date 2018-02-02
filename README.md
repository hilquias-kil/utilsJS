# utilsJS

## Immutable change

change a item in the array by index, and return new array.

```js
const insertByIndex = (state, newItem, insertAt) =>
[
  ...state.slice(0, insertAt),
  newItem,
  ...state.slice(insertAt, state.length - 1)
]
```
