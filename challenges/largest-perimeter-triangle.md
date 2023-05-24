# 976. Largest Perimeter Triangle

<br />Given an integer array `nums`, return <em>the largest perimeter of a triangle with a non-zero area, formed from three of these lengths</em>. If it is impossible to form any triangle of a non-zero area, return `0`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [2,1,2]
Output: 5
Explanation: You can form a triangle with three side lengths: 1, 2, and 2.
```
<br />**Example 2:**<br />
```
Input: nums = [1,2,1,10]
Output: 0
Explanation: 
You cannot use the side lengths 1, 1, and 2 to form a triangle.
You cannot use the side lengths 1, 1, and 10 to form a triangle.
You cannot use the side lengths 1, 2, and 10 to form a triangle.
As we cannot use any three side lengths to form a triangle of non-zero area, we return 0.
```
<br /> <br />
<br />**Constraints:**<br />

* `3 <;= nums.length <;= 10<sup>4</sup>`

* `1 <;= nums[i] <;= 10<sup>6</sup>`