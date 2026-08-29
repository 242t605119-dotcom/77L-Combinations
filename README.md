# LeetCode 77 – Combinations

Given two integers `n` and `k`, return all possible combinations of `k` numbers chosen from the range `[1, n]`.

The order of the numbers does not matter.

## Example

### Input

```text
n = 4
k = 2
```

### Output

```text
[
 [1,2],
 [1,3],
 [1,4],
 [2,3],
 [2,4],
 [3,4]
]
```

## Approach

I used **Backtracking** to generate all possible combinations.

Starting from each number, I choose the next number and continue until the combination contains `k` numbers.

After storing a combination, I remove the last number and try another possibility.

## Complexity

* **Time Complexity:** `O(C(N,K) × K)`
* **Space Complexity:** `O(K)` excluding the output.

## Language

**Python**

## LeetCode

**Problem:** 77. Combinations
**Difficulty:** Medium
**Topic:** Backtracking, Array

## Author

T.Nandhini
