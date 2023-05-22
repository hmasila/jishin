# 1089. Duplicate Zeros

<br />Given a fixed-length integer array `arr`, duplicate each occurrence of zero, shifting the remaining elements to the right.<br />
<br />**Note** that elements beyond the length of the original array are not written. Do the above modifications to the input array in place and do not return anything.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: arr = [1,0,2,3,0,4,5,0]
Output: [1,0,0,2,3,0,0,4]
Explanation: After calling your function, the input array is modified to: [1,0,0,2,3,0,0,4]
```
<br />**Example 2:**<br />
```
Input: arr = [1,2,3]
Output: [1,2,3]
Explanation: After calling your function, the input array is modified to: [1,2,3]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= arr.length <;= 10<sup>4</sup>`

* `0 <;= arr[i] <;= 9`