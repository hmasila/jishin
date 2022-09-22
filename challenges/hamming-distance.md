# 461. Hamming Distance

<br />The <a href="https://en.wikipedia.org/wiki/Hamming_distance" target="_blank">Hamming distance</a> between two integers is the number of positions at which the corresponding bits are different.<br />
<br />Given two integers `x` and `y`, return <em>the **Hamming distance** between them</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: x = 1, y = 4
Output: 2
Explanation:
1   (0 0 0 1)
4   (0 1 0 0)
       ↑   ↑
The above arrows point to positions where the corresponding bits are different.
```
<br />**Example 2:**<br />
```
Input: x = 3, y = 1
Output: 1
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= x, y <;= 2<sup>31</sup> - 1`