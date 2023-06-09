# 1991. Find the Middle Index in Array

<br />Given a **0-indexed** integer array `nums`, find the **leftmost** `middleIndex` (i.e., the smallest amongst all the possible ones).<br />
<br />A `middleIndex` is an index where `nums[0] + nums[1] + ... + nums[middleIndex-1] == nums[middleIndex+1] + nums[middleIndex+2] + ... + nums[nums.length-1]`.<br />
<br />If `middleIndex == 0`, the left side sum is considered to be `0`. Similarly, if `middleIndex == nums.length - 1`, the right side sum is considered to be `0`.<br />
<br />Return <em>the **leftmost** </em>`middleIndex`<em> that satisfies the condition, or </em>`-1`<em> if there is no such index</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [2,3,-1,<u>8</u>,4]
Output: 3
Explanation: The sum of the numbers before index 3 is: 2 + 3 + -1 = 4
The sum of the numbers after index 3 is: 4 = 4
```
<br />**Example 2:**<br />
```
Input: nums = [1,-1,<u>4</u>]
Output: 2
Explanation: The sum of the numbers before index 2 is: 1 + -1 = 0
The sum of the numbers after index 2 is: 0
```
<br />**Example 3:**<br />
```
Input: nums = [2,5]
Output: -1
Explanation: There is no valid middleIndex.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 100`

* `-1000 <;= nums[i] <;= 1000`


<br /> <br />
<br />**Note:** This question is the same as 724: <a href="https://leetcode.com/problems/find-pivot-index/" target="_blank">https://leetcode.com/problems/find-pivot-index/</a><br />