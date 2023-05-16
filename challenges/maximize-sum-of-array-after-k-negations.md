# 1005. Maximize Sum Of Array After K Negations

<br />Given an integer array `nums` and an integer `k`, modify the array in the following way:<br />

* choose an index `i` and replace `nums[i]` with `-nums[i]`.


<br />You should apply this process exactly `k` times. You may choose the same index `i` multiple times.<br />
<br />Return <em>the largest possible sum of the array after modifying it in this way</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [4,2,3], k = 1
Output: 5
Explanation: Choose index 1 and nums becomes [4,-2,3].
```
<br />**Example 2:**<br />
```
Input: nums = [3,-1,0,2], k = 3
Output: 6
Explanation: Choose indices (1, 2, 2) and nums becomes [3,1,0,2].
```
<br />**Example 3:**<br />
```
Input: nums = [2,-3,-1,5,-4], k = 2
Output: 13
Explanation: Choose indices (1, 4) and nums becomes [2,3,-1,5,4].
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 10<sup>4</sup>`

* `-100 <;= nums[i] <;= 100`

* `1 <;= k <;= 10<sup>4</sup>`