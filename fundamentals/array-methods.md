## Use to run different operations on arrays. In a lot cases, they replace for-loops and make code more readable.

### map

Useful when wanting to do something to every item in an array. Map takes a callback function that gets called on every item and returns a new array.

Ex:

```
const colors = ["red", "blue", "green"];

const pluralColors = colors.map(color => {
    return `${color}s`;
});

// pluralColors = ["reds", "blues", "greens"]
```

### filter

Useful when wanting to separate item in an array that pass some type of criteria. Filter takes a callback function containing the "test" that gets called on every item and returns a new array with the filtered item(s).

Ex:

```
const nums = [4, 50, 20, 9, 47, 12, 33];

const evenNums = nums.filter(num => num % 2 === 0);

// evenNums = [4, 50, 20, 12]
```
