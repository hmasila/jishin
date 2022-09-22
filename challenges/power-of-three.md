# 326. Power of Three

<br />Given an integer `n`, return <em>`true` if it is a power of three. Otherwise, return `false`</em>.<br />
<br />An integer `n` is a power of three, if there exists an integer `x` such that `n == 3<sup>x</sup>`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 27
Output: true
Explanation: 27 = 3<sup>3</sup>
```
<br />**Example 2:**<br />
```
Input: n = 0
Output: false
Explanation: There is no x where 3<sup>x</sup> = 0.
```
<br />**Example 3:**<br />
```
Input: n = -1
Output: false
Explanation: There is no x where 3<sup>x</sup> = (-1).
```
<br /> <br />
<br />**Constraints:**<br />

* `-2<sup>31</sup> <;= n <;= 2<sup>31</sup> - 1`


<br /> <br />
**Follow up:** Could you solve it without loops/recursion?