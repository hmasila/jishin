# 1752. Check if Array Is Sorted and Rotated

<br />Given an array `nums`, return `true`<em> if the array was originally sorted in non-decreasing order, then rotated **some** number of positions (including zero)</em>. Otherwise, return `false`.<br />
<br />There may be **duplicates** in the original array.<br />
<br />**Note:** An array `A` rotated by `x` positions results in an array `B` of the same length such that `A[i] == B[(i+x) % A.length]`, where `%` is the modulo operation.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [3,4,5,1,2]
Output: true
Explanation: [1,2,3,4,5] is the original sorted array.
You can rotate the array by x = 3 positions to begin on the the element of value 3: [3,4,5,1,2].
```
<br />**Example 2:**<br />
```
Input: nums = [2,1,3,4]
Output: false
Explanation: There is no sorted array once rotated that can make nums.
```
<br />**Example 3:**<br />
```
Input: nums = [1,2,3]
Output: true
Explanation: [1,2,3] is the original sorted array.
You can rotate the array by x = 0 positions (i.e. no rotation) to make nums.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 100`

* `1 <;= nums[i] <;= 100`