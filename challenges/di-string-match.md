# 942. DI String Match

<br />A permutation `perm` of `n + 1` integers of all the integers in the range `[0, n]` can be represented as a string `s` of length `n` where:<br />

* `s[i] == 'I'` if `perm[i] <; perm[i + 1]`, and

* `s[i] == 'D'` if `perm[i] >; perm[i + 1]`.


<br />Given a string `s`, reconstruct the permutation `perm` and return it. If there are multiple valid permutations perm, return **any of them**.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "IDID"
Output: [0,4,1,3,2]
```<br />**Example 2:**<br />
```
Input: s = "III"
Output: [0,1,2,3]
```<br />**Example 3:**<br />
```
Input: s = "DDI"
Output: [3,2,0,1]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 10<sup>5</sup>`

* `s[i]` is either `'I'` or `'D'`.