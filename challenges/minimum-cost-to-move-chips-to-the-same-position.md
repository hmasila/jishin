# 1217. Minimum Cost to Move Chips to The Same Position

<br />We have `n` chips, where the position of the `i<sup>th</sup>` chip is `position[i]`.<br />
<br />We need to move all the chips to **the same position**. In one step, we can change the position of the `i<sup>th</sup>` chip from `position[i]` to:<br />

* `position[i] + 2` or `position[i] - 2` with `cost = 0`.

* `position[i] + 1` or `position[i] - 1` with `cost = 1`.


<br />Return <em>the minimum cost</em> needed to move all the chips to the same position.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/08/15/chips_e1.jpg" style="width:750px;height:217px"/>
```
Input: position = [1,2,3]
Output: 1
Explanation: First step: Move the chip at position 3 to position 1 with cost = 0.
Second step: Move the chip at position 2 to position 1 with cost = 1.
Total cost is 1.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/08/15/chip_e2.jpg" style="width:750px;height:306px"/>
```
Input: position = [2,2,2,3,3]
Output: 2
Explanation: We can move the two chips at position  3 to position 2. Each move has cost = 1. The total cost = 2.
```
<br />**Example 3:**<br />
```
Input: position = [1,1000000000]
Output: 1
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= position.length <;= 100`

* `1 <;= position[i] <;= 10^9`