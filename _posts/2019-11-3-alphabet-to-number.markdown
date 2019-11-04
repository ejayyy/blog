---
layout: post
---
### transfer alphabet to number
- `[char].charCodeAt(0)` : a = 97, b = 98....

### enhanced for loop
- `for(item in ary)` : item = index
- `for(item of ary)` : item = ary[i]

### sum of each alphabet
- `const wordsToMarks = s => [...s].reduce((res, c) => res += c.charCodeAt() - 96, 0)`
    - point of view : string to arr, default value
    - JS [reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce) function : `arr.reduce(callback(accumulator, currentValue[, index[, array]])[, initialValue])`