# 1560. Most Visited Sector in  a Circular Track

<br />Given an integer `n` and an integer array `rounds`. We have a circular track which consists of `n` sectors labeled from `1` to `n`. A marathon will be held on this track, the marathon consists of `m` rounds. The `i<sup>th</sup>` round starts at sector `rounds[i - 1]` and ends at sector `rounds[i]`. For example, round 1 starts at sector `rounds[0]` and ends at sector `rounds[1]`<br />
<br />Return <em>an array of the most visited sectors</em> sorted in **ascending** order.<br />
<br />Notice that you circulate the track in ascending order of sector numbers in the counter-clockwise direction (See the first example).<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/08/14/tmp.jpg" style="width:433px;height:341px"/>
```
Input: n = 4, rounds = [1,3,1,2]
Output: [1,2]
Explanation: The marathon starts at sector 1. The order of the visited sectors is as follows:
1 -->; 2 -->; 3 (end of round 1) -->; 4 -->; 1 (end of round 2) -->; 2 (end of round 3 and the marathon)
We can see that both sectors 1 and 2 are visited twice and they are the most visited sectors. Sectors 3 and 4 are visited only once.```
<br />**Example 2:**<br />
```
Input: n = 2, rounds = [2,1,2,1,2,1,2,1,2]
Output: [2]
```
<br />**Example 3:**<br />
```
Input: n = 7, rounds = [1,3,5,7]
Output: [1,2,3,4,5,6,7]
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= n <;= 100`

* `1 <;= m <;= 100`

* `rounds.length == m + 1`

* `1 <;= rounds[i] <;= n`

* `rounds[i] != rounds[i + 1]` for `0 <;= i <; m`