# Simple Array Sum
Given an array of integers, find the sum of its elements.

## Solution

### kotlin
```kt
fun simpleArraySum(ar: Array<Int>) = if (ar.size > 1000) 0 else ar.sum()
```