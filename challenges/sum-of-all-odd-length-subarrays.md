# 1588. Sum of All Odd Length Subarrays

<br />Given an array of positive integers `arr`, return <em>the sum of all possible **odd-length subarrays** of </em>`arr`.<br />
<br />A **subarray** is a contiguous subsequence of the array.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [1,4,2,5,3]
Output: 58
**Explanation: **The odd-length subarrays of arr and their sums are:
[1] = 1
[4] = 4
[2] = 2
[5] = 5
[3] = 3
[1,4,2] = 7
[4,2,5] = 11
[2,5,3] = 10
[1,4,2,5,3] = 15
If we add all these together we get 1 + 4 + 2 + 5 + 3 + 7 + 11 + 10 + 15 = 58```
<br />**Example 2:**<br />
```
Input: arr = [1,2]
Output: 3
<b>Explanation: </b>There are only 2 subarrays of odd length, [1] and [2]. Their sum is 3.```
<br />**Example 3:**<br />
```
Input: arr = [10,11,12]
Output: 66
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= arr.length <;= 100`

* `1 <;= arr[i] <;= 1000`


<br /> <br />
<br />**Follow up:**<br />
<br />Could you solve this problem in O(n) time complexity?<br />