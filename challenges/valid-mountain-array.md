# 941. Valid Mountain Array

<br />Given an array of integers `arr`, return <em>`true` if and only if it is a valid mountain array</em>.<br />
<br />Recall that arr is a mountain array if and only if:<br />

* `arr.length >;= 3`

<li>There exists some `i` with `0 <; i <; arr.length - 1` such that:
	
* `arr[0] <; arr[1] <; ... <; arr[i - 1] <; arr[i] `

* `arr[i] >; arr[i + 1] >; ... >; arr[arr.length - 1]`


</li>

<img src="https://assets.leetcode.com/uploads/2019/10/20/hint_valid_mountain_array.png" width="500"/>
<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [2,1]
Output: false
```<br />**Example 2:**<br />
```
Input: arr = [3,5,5]
Output: false
```<br />**Example 3:**<br />
```
Input: arr = [0,3,2,1]
Output: true
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= arr.length <;= 10<sup>4</sup>`

* `0 <;= arr[i] <;= 10<sup>4</sup>`