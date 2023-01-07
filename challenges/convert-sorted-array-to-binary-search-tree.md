# 108. Convert Sorted Array to Binary Search Tree

<br />Given an integer array `nums` where the elements are sorted in **ascending order**, convert <em>it to a </em><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="height-balanced">**<em>height-balanced</em>**</span> <em>binary search tree</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/18/btree1.jpg" style="width: 302px; height: 222px;"/>
```
Input: nums = [-10,-3,0,5,9]
Output: [0,-3,9,-10,null,5]
Explanation: [0,-10,5,null,-3,null,9] is also accepted:
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/18/btree2.jpg" style="width: 302px; height: 222px;"/>
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/18/btree.jpg" style="width: 342px; height: 142px;"/>
```
Input: nums = [1,3]
Output: [3,1]
Explanation: [1,null,3] and [3,1] are both height-balanced BSTs.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 10<sup>4</sup>`

* `-10<sup>4</sup> <;= nums[i] <;= 10<sup>4</sup>`

* `nums` is sorted in a **strictly increasing** order.