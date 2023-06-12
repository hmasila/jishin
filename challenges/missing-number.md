# 268. Missing Number

<br />Given an array `nums` containing `n` distinct numbers in the range `[0, n]`, return <em>the only number in the range that is missing from the array.</em><br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [3,0,1]
Output: 2
Explanation: n = 3 since there are 3 numbers, so all numbers are in the range [0,3]. 2 is the missing number in the range since it does not appear in nums.
```
<br />**Example 2:**<br />
```
Input: nums = [0,1]
Output: 2
Explanation: n = 2 since there are 2 numbers, so all numbers are in the range [0,2]. 2 is the missing number in the range since it does not appear in nums.
```
<br />**Example 3:**<br />
```
Input: nums = [9,6,4,2,3,5,7,0,1]
Output: 8
Explanation: n = 9 since there are 9 numbers, so all numbers are in the range [0,9]. 8 is the missing number in the range since it does not appear in nums.
```
<br /> <br />
<br />**Constraints:**<br />

* `n == nums.length`

* `1 <;= n <;= 10<sup>4</sup>`

* `0 <;= nums[i] <;= n`

* All the numbers of `nums` are **unique**.


<br /> <br />
<br />**Follow up:** Could you implement a solution using only `O(1)` extra space complexity and `O(n)` runtime complexity?<br />