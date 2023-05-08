# 961. N-Repeated Element in Size 2N Array

<br />You are given an integer array `nums` with the following properties:<br />

* `nums.length == 2 * n`.

* `nums` contains `n + 1` **unique** elements.

* Exactly one element of `nums` is repeated `n` times.


<br />Return <em>the element that is repeated </em>`n`<em> times</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,2,3,3]
Output: 3
```<br />**Example 2:**<br />
```
Input: nums = [2,1,2,5,3,2]
Output: 2
```<br />**Example 3:**<br />
```
Input: nums = [5,1,5,2,5,3,5,4]
Output: 5
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= n <;= 5000`

* `nums.length == 2 * n`

* `0 <;= nums[i] <;= 10<sup>4</sup>`

* `nums` contains `n + 1` **unique** elements and one of them is repeated exactly `n` times.