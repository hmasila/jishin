# 1331. Rank Transform of an Array

<br />Given an array of integers `arr`, replace each element with its rank.<br />
<br />The rank represents how large the element is. The rank has the following rules:<br />

* Rank is an integer starting from 1.

* The larger the element, the larger the rank. If two elements are equal, their rank must be the same.

* Rank should be as small as possible.


<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [40,10,20,30]
Output: [4,1,2,3]
**Explanation**: 40 is the largest element. 10 is the smallest. 20 is the second smallest. 30 is the third smallest.```
<br />**Example 2:**<br />
```
Input: arr = [100,100,100]
Output: [1,1,1]
**Explanation**: Same elements share the same rank.
```
<br />**Example 3:**<br />
```
Input: arr = [37,12,28,9,100,56,80,5,12]
Output: [5,3,4,2,8,6,7,1,3]
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= arr.length <;= 10<sup>5</sup>`

* `-10<sup>9</sup> <;= arr[i] <;= 10<sup>9</sup>`