# Simple Array Sum
Given an array of integers, find the sum of its elements.

## Solution

### kotlin
```kt
fun simpleArraySum(ar: Array<Int>): Int {
    // Write your code here
    var acc = 0
    for(v in ar) {
        acc += v
    }
    
    return acc
}

```

### typescript
```ts
function simpleArraySum(ar: number[]): number {
    // Write your code here
    return ar.reduce((acc, v) => {
        return acc+v
    }, 0)
}
```
