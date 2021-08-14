# 747. Largest Number At Least Twice of Others

<br />You are given an integer array `nums` where the largest integer is **unique**.<br />
<br />Determine whether the largest element in the array is **at least twice** as much as every other number in the array. If it is, return <em>the **index** of the largest element, or return </em>`-1`<em> otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [3,6,1,0]
Output: 1
Explanation: 6 is the largest integer.
For every other number in the array x, 6 is at least twice as big as x.
The index of value 6 is 1, so we return 1.
```
<br />**Example 2:**<br />
```
Input: nums = [1,2,3,4]
Output: -1
Explanation: 4 is less than twice the value of 3, so we return -1.
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= nums.length <;= 50`

* `0 <;= nums[i] <;= 100`

* The largest element in `nums` is unique.