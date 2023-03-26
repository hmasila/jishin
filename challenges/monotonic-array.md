# 896. Monotonic Array

<br />An array is **monotonic** if it is either monotone increasing or monotone decreasing.<br />
<br />An array `nums` is monotone increasing if for all `i <;= j`, `nums[i] <;= nums[j]`. An array `nums` is monotone decreasing if for all `i <;= j`, `nums[i] >;= nums[j]`.<br />
<br />Given an integer array `nums`, return `true`<em> if the given array is monotonic, or </em>`false`<em> otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,2,2,3]
Output: true
```
<br />**Example 2:**<br />
```
Input: nums = [6,5,4,4]
Output: true
```
<br />**Example 3:**<br />
```
Input: nums = [1,3,2]
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 10<sup>5</sup>`

* `-10<sup>5</sup> <;= nums[i] <;= 10<sup>5</sup>`