# 350. Intersection of Two Arrays II

<br />Given two integer arrays `nums1` and `nums2`, return <em>an array of their intersection</em>. Each element in the result must appear as many times as it shows in both arrays and you may return the result in **any order**.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums1 = [1,2,2,1], nums2 = [2,2]
Output: [2,2]
```
<br />**Example 2:**<br />
```
Input: nums1 = [4,9,5], nums2 = [9,4,9,8,4]
Output: [4,9]
Explanation: [9,4] is also accepted.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums1.length, nums2.length <;= 1000`

* `0 <;= nums1[i], nums2[i] <;= 1000`


<br /> <br />
<br />**Follow up:**<br />

* What if the given array is already sorted? How would you optimize your algorithm?

* What if `nums1`'s size is small compared to `nums2`'s size? Which algorithm is better?

* What if elements of `nums2` are stored on disk, and the memory is limited such that you cannot load all elements into the memory at once?