# 1827. Minimum Operations to Make the Array Increasing

<br />You are given an integer array `nums` (**0-indexed**). In one operation, you can choose an element of the array and increment it by `1`.<br />

* For example, if `nums = [1,2,3]`, you can choose to increment `nums[1]` to make `nums = [1,<u><b>3</b></u>,3]`.


<br />Return <em>the **minimum** number of operations needed to make</em> `nums` <em>**strictly** **increasing**.</em><br />
<br />An array `nums` is **strictly increasing** if `nums[i] <; nums[i+1]` for all `0 <;= i <; nums.length - 1`. An array of length `1` is trivially strictly increasing.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,1,1]
Output: 3
Explanation: You can do the following operations:
1) Increment nums[2], so nums becomes [1,1,<u>**2**</u>].
2) Increment nums[1], so nums becomes [1,<u>**2**</u>,2].
3) Increment nums[2], so nums becomes [1,2,<u>**3**</u>].
```
<br />**Example 2:**<br />
```
Input: nums = [1,5,2,4,1]
Output: 14
```
<br />**Example 3:**<br />
```
Input: nums = [8]
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 5000`

* `1 <;= nums[i] <;= 10<sup>4</sup>`