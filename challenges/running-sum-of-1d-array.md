# 1480. Running Sum of 1d Array

<br />Given an array `nums`. We define a running sum of an array as `runningSum[i] = sum(nums[0]…nums[i])`.<br />
<br />Return the running sum of `nums`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,2,3,4]
Output: [1,3,6,10]
Explanation: Running sum is obtained as follows: [1, 1+2, 1+2+3, 1+2+3+4].```
<br />**Example 2:**<br />
```
Input: nums = [1,1,1,1,1]
Output: [1,2,3,4,5]
Explanation: Running sum is obtained as follows: [1, 1+1, 1+1+1, 1+1+1+1, 1+1+1+1+1].```
<br />**Example 3:**<br />
```
Input: nums = [3,1,2,10,1]
Output: [3,4,6,16,17]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 1000`

* `-10^6 <;= nums[i] <;= 10^6`