# 1502. Can Make Arithmetic Progression From Sequence

<br />A sequence of numbers is called an **arithmetic progression** if the difference between any two consecutive elements is the same.<br />
<br />Given an array of numbers `arr`, return `true` <em>if the array can be rearranged to form an **arithmetic progression**. Otherwise, return</em> `false`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [3,5,1]
Output: true
**Explanation: **We can reorder the elements as [1,3,5] or [5,3,1] with differences 2 and -2 respectively, between each consecutive elements.
```
<br />**Example 2:**<br />
```
Input: arr = [1,2,4]
Output: false
**Explanation: **There is no way to reorder the elements to obtain an arithmetic progression.
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= arr.length <;= 1000`

* `-10<sup>6</sup> <;= arr[i] <;= 10<sup>6</sup>`