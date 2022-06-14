# 1486. XOR Operation in an Array

<br />You are given an integer `n` and an integer `start`.<br />
<br />Define an array `nums` where `nums[i] = start + 2 * i` (**0-indexed**) and `n == nums.length`.<br />
<br />Return <em>the bitwise XOR of all elements of</em> `nums`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 5, start = 0
Output: 8
Explanation: Array nums is equal to [0, 2, 4, 6, 8] where (0 ^ 2 ^ 4 ^ 6 ^ 8) = 8.
Where "^" corresponds to bitwise XOR operator.
```
<br />**Example 2:**<br />
```
Input: n = 4, start = 3
Output: 8
Explanation: Array nums is equal to [3, 5, 7, 9] where (3 ^ 5 ^ 7 ^ 9) = 8.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 1000`

* `0 <;= start <;= 1000`

* `n == nums.length`