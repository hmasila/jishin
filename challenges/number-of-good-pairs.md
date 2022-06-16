# 1512. Number of Good Pairs

<br />Given an array of integers `nums`, return <em>the number of **good pairs**</em>.<br />
<br />A pair `(i, j)` is called <em>good</em> if `nums[i] == nums[j]` and `i` <; `j`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,2,3,1,1,3]
Output: 4
Explanation: There are 4 good pairs (0,3), (0,4), (3,4), (2,5) 0-indexed.
```
<br />**Example 2:**<br />
```
Input: nums = [1,1,1,1]
Output: 6
Explanation: Each pair in the array are <em>good</em>.
```
<br />**Example 3:**<br />
```
Input: nums = [1,2,3]
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 100`

* `1 <;= nums[i] <;= 100`