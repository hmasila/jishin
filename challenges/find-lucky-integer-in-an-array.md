# 1394. Find Lucky Integer in an Array

<br />Given an array of integers `arr`, a **lucky integer** is an integer that has a frequency in the array equal to its value.<br />
<br />Return <em>the largest **lucky integer** in the array</em>. If there is no **lucky integer** return `-1`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [2,2,3,4]
Output: 2
Explanation: The only lucky number in the array is 2 because frequency[2] == 2.
```
<br />**Example 2:**<br />
```
Input: arr = [1,2,2,3,3,3]
Output: 3
Explanation: 1, 2 and 3 are all lucky numbers, return the largest of them.
```
<br />**Example 3:**<br />
```
Input: arr = [2,2,2,3,3]
Output: -1
Explanation: There are no lucky numbers in the array.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= arr.length <;= 500`

* `1 <;= arr[i] <;= 500`