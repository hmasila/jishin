# 1800. Maximum Ascending Subarray Sum

<br />Given an array of positive integers `nums`, return the <em>maximum possible sum of an **ascending** subarray in </em>`nums`.<br />
<br />A subarray is defined as a contiguous sequence of numbers in an array.<br />
<br />A subarray `[nums<sub>l</sub>, nums<sub>l+1</sub>, ..., nums<sub>r-1</sub>, nums<sub>r</sub>]` is **ascending** if for all `i` where `l <;= i <; r`, `nums<sub>i </sub> <; nums<sub>i+1</sub>`. Note that a subarray of size `1` is **ascending**.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [10,20,30,5,10,50]
Output: 65
**Explanation: **[5,10,50] is the ascending subarray with the maximum sum of 65.
```
<br />**Example 2:**<br />
```
Input: nums = [10,20,30,40,50]
Output: 150
**Explanation: **[10,20,30,40,50] is the ascending subarray with the maximum sum of 150.
```
<br />**Example 3:**<br />
```
Input: nums = [12,17,15,13,10,11,12]
Output: 33
**Explanation: **[10,11,12] is the ascending subarray with the maximum sum of 33.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 100`

* `1 <;= nums[i] <;= 100`