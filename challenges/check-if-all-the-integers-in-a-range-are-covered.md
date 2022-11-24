# 1893. Check if All the Integers in a Range Are Covered

<br />You are given a 2D integer array `ranges` and two integers `left` and `right`. Each `ranges[i] = [start<sub>i</sub>, end<sub>i</sub>]` represents an **inclusive** interval between `start<sub>i</sub>` and `end<sub>i</sub>`.<br />
<br />Return `true` <em>if each integer in the inclusive range</em> `[left, right]` <em>is covered by **at least one** interval in</em> `ranges`. Return `false` <em>otherwise</em>.<br />
<br />An integer `x` is covered by an interval `ranges[i] = [start<sub>i</sub>, end<sub>i</sub>]` if `start<sub>i</sub> <;= x <;= end<sub>i</sub>`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: ranges = [[1,2],[3,4],[5,6]], left = 2, right = 5
Output: true
Explanation: Every integer between 2 and 5 is covered:
- 2 is covered by the first range.
- 3 and 4 are covered by the second range.
- 5 is covered by the third range.
```
<br />**Example 2:**<br />
```
Input: ranges = [[1,10],[10,20]], left = 21, right = 21
Output: false
Explanation: 21 is not covered by any range.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= ranges.length <;= 50`

* `1 <;= start<sub>i</sub> <;= end<sub>i</sub> <;= 50`

* `1 <;= left <;= right <;= 50`