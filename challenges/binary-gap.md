# 868. Binary Gap

<br />Given a positive integer `n`, find and return <em>the **longest distance** between any two **adjacent** </em>`1`<em>'s in the binary representation of </em>`n`<em>. If there are no two adjacent </em>`1`<em>'s, return </em>`0`<em>.</em><br />
<br />Two `1`'s are **adjacent** if there are only `0`'s separating them (possibly no `0`'s). The <b>distance</b> between two `1`'s is the absolute difference between their bit positions. For example, the two `1`'s in `"1001"` have a distance of 3.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 22
Output: 2
Explanation: 22 in binary is "10110".
The first adjacent pair of 1's is "<u>1</u>0<u>1</u>10" with a distance of 2.
The second adjacent pair of 1's is "10<u>11</u>0" with a distance of 1.
The answer is the largest of these two distances, which is 2.
Note that "<u>1</u>01<u>1</u>0" is not a valid pair since there is a 1 separating the two 1's underlined.
```
<br />**Example 2:**<br />
```
Input: n = 8
Output: 0
Explanation: 8 in binary is "1000".
There are not any adjacent pairs of 1's in the binary representation of 8, so we return 0.
```
<br />**Example 3:**<br />
```
Input: n = 5
Output: 2
Explanation: 5 in binary is "101".
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 10<sup>9</sup>`