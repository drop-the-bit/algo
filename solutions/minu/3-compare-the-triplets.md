# Compare the Triplets
https://www.hackerrank.com/challenges/compare-the-triplets/problem

## Solution

### kotlin
```kt
fun compareTriplets(a: Array<Int>, b: Array<Int>): Array<Int> {
    if (a.size != b.size) {
        return emptyArray()
    }

    var aliceScore = 0
    var bobScore = 0

    val limit = a.size - 1
    for (it in 0..limit) {
        val result = a[it].compareTo(b[it])
        if (result > 0) aliceScore++
        else if (result < 0) bobScore++
        else continue
    }

    return arrayOf(aliceScore, bobScore)
}
```