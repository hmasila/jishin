# 1299. Replace Elements with Greatest Element on Right Side

<br />Given an array `arr`, replace every element in that array with the greatest element among the elements to its right, and replace the last element with `-1`.<br />
<br />After doing so, return the array.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [17,18,5,4,6,1]
Output: [18,6,6,6,1,-1]
Explanation: 
- index 0 -->; the greatest element to the right of index 0 is index 1 (18).
- index 1 -->; the greatest element to the right of index 1 is index 4 (6).
- index 2 -->; the greatest element to the right of index 2 is index 4 (6).
- index 3 -->; the greatest element to the right of index 3 is index 4 (6).
- index 4 -->; the greatest element to the right of index 4 is index 5 (1).
- index 5 -->; there are no elements to the right of index 5, so we put -1.
```
<br />**Example 2:**<br />
```
Input: arr = [400]
Output: [-1]
Explanation: There are no elements to the right of index 0.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= arr.length <;= 10<sup>4</sup>`

* `1 <;= arr[i] <;= 10<sup>5</sup>`