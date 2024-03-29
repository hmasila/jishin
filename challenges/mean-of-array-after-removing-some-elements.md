# 1619. Mean of Array After Removing Some Elements

<br />Given an integer array `arr`, return <em>the mean of the remaining integers after removing the smallest `5%` and the largest `5%` of the elements.</em><br />
<br />Answers within `10<sup>-5</sup>` of the **actual answer** will be considered accepted.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [1,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,3]
Output: 2.00000
Explanation: After erasing the minimum and the maximum values of this array, all elements are equal to 2, so the mean is 2.
```
<br />**Example 2:**<br />
```
Input: arr = [6,2,7,5,1,2,0,3,10,2,5,0,5,5,0,8,7,6,8,0]
Output: 4.00000
```
<br />**Example 3:**<br />
```
Input: arr = [6,0,7,0,7,5,7,8,3,4,0,7,8,1,6,8,1,1,2,4,8,1,9,5,4,3,8,5,10,8,6,6,1,0,6,10,8,2,3,4]
Output: 4.77778
```
<br /> <br />
<br />**Constraints:**<br />

* `20 <;= arr.length <;= 1000`

* `arr.length`<b> </b>**is a multiple** of `20`.

* `<font face="monospace">0 <;= arr[i] <;= 10<sup>5</sup></font>`