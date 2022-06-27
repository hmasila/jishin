# 1528. Shuffle String

<br />You are given a string `s` and an integer array `indices` of the **same length**. The string `s` will be shuffled such that the character at the `i<sup>th</sup>` position moves to `indices[i]` in the shuffled string.<br />
<br />Return <em>the shuffled string</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/07/09/q1.jpg" style="width:321px;height:243px"/>
```
Input: s = "codeleet", `indices` = [4,5,6,7,0,2,1,3]
Output: "leetcode"
Explanation: As shown, "codeleet" becomes "leetcode" after shuffling.
```
<br />**Example 2:**<br />
```
Input: s = "abc", `indices` = [0,1,2]
Output: "abc"
Explanation: After shuffling, each character remains in its position.
```
<br /> <br />
<br />**Constraints:**<br />

* `s.length == indices.length == n`

* `1 <;= n <;= 100`

* `s` consists of only lowercase English letters.

* `0 <;= indices[i] <; n`

* All values of `indices` are **unique**.