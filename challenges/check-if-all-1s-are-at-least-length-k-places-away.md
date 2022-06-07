# 1437. Check If All 1's Are at Least Length K Places Away

<br />Given an binary array `nums` and an integer `k`, return `true`<em> if all </em>`1`<em>'s are at least </em>`k`<em> places away from each other, otherwise return </em>`false`.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/04/15/sample_1_1791.png" style="width:428px;height:181px"/>
```
Input: nums = [1,0,0,0,1,0,0,1], k = 2
Output: true
Explanation: Each of the 1s are at least 2 places away from each other.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/04/15/sample_2_1791.png" style="width:320px;height:173px"/>
```
Input: nums = [1,0,0,1,0,1], k = 2
Output: false
Explanation: The second 1 and third 1 are only one apart from each other.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 10<sup>5</sup>`

* `0 <;= k <;= nums.length`

* `nums[i]` is `0` or `1`