# 219. Contains Duplicate II

<br />Given an integer array `nums` and an integer `k`, return `true` <em>if there are two **distinct indices** </em>`i`<em> and </em>`j`<em> in the array such that </em>`nums[i] == nums[j]`<em> and </em>`abs(i - j) <;= k`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,2,3,1], k = 3
Output: true
```
<br />**Example 2:**<br />
```
Input: nums = [1,0,1,1], k = 1
Output: true
```
<br />**Example 3:**<br />
```
Input: nums = [1,2,3,1,2,3], k = 2
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 10<sup>5</sup>`

* `-10<sup>9</sup> <;= nums[i] <;= 10<sup>9</sup>`

* `0 <;= k <;= 10<sup>5</sup>`