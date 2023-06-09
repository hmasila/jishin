# 1995. Count Special Quadruplets

<br />Given a **0-indexed** integer array `nums`, return <em>the number of **distinct** quadruplets</em> `(a, b, c, d)` <em>such that:</em><br />

* `nums[a] + nums[b] + nums[c] == nums[d]`, and

* `a <; b <; c <; d`


<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,2,3,6]
Output: 1
Explanation: The only quadruplet that satisfies the requirement is (0, 1, 2, 3) because 1 + 2 + 3 == 6.
```
<br />**Example 2:**<br />
```
Input: nums = [3,3,6,4,5]
Output: 0
Explanation: There are no such quadruplets in [3,3,6,4,5].
```
<br />**Example 3:**<br />
```
Input: nums = [1,1,1,3,5]
Output: 4
Explanation: The 4 quadruplets that satisfy the requirement are:
- (0, 1, 2, 3): 1 + 1 + 1 == 3
- (0, 1, 3, 4): 1 + 1 + 3 == 5
- (0, 2, 3, 4): 1 + 1 + 3 == 5
- (1, 2, 3, 4): 1 + 1 + 3 == 5
```
<br /> <br />
<br />**Constraints:**<br />

* `4 <;= nums.length <;= 50`

* `1 <;= nums[i] <;= 100`