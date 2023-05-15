# 914. X of a Kind in a Deck of Cards

<br />You are given an integer array `deck` where `deck[i]` represents the number written on the `i<sup>th</sup>` card.<br />
<br />Partition the cards into **one or more groups** such that:<br />

* Each group has **exactly** `x` cards where `x >; 1`, and

* All the cards in one group have the same integer written on them.


<br />Return `true`<em> if such partition is possible, or </em>`false`<em> otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: deck = [1,2,3,4,4,3,2,1]
Output: true
**Explanation**: Possible partition [1,1],[2,2],[3,3],[4,4].
```
<br />**Example 2:**<br />
```
Input: deck = [1,1,1,2,2,2,3,3]
Output: false
**Explanation**: No possible partition.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= deck.length <;= 10<sup>4</sup>`

* `0 <;= deck[i] <; 10<sup>4</sup>`