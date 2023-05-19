# 977. Squares of a Sorted Array

<br />Given an integer array `nums` sorted in **non-decreasing** order, return <em>an array of **the squares of each number** sorted in non-decreasing order</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [-4,-1,0,3,10]
Output: [0,1,9,16,100]
Explanation: After squaring, the array becomes [16,1,0,9,100].
After sorting, it becomes [0,1,9,16,100].
```
<br />**Example 2:**<br />
```
Input: nums = [-7,-3,2,3,11]
Output: [4,9,9,49,121]
```
<br /> <br />
<br />**Constraints:**<br />

* `<span>1 <;= nums.length <;= </span>10<sup>4</sup>`

* `-10<sup>4</sup> <;= nums[i] <;= 10<sup>4</sup>`

* `nums` is sorted in **non-decreasing** order.


<br /> <br />
**Follow up:** Squaring each element and sorting the new array is very trivial, could you find an `O(n)` solution using a different approach?