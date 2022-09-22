# 338. Counting Bits

<br />Given an integer `n`, return <em>an array </em>`ans`<em> of length </em>`n + 1`<em> such that for each </em>`i`<em> </em>(`0 <;= i <;= n`)<em>, </em>`ans[i]`<em> is the **number of **</em>`1`<em>**'s** in the binary representation of </em>`i`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 2
Output: [0,1,1]
Explanation:
0 -->; 0
1 -->; 1
2 -->; 10
```
<br />**Example 2:**<br />
```
Input: n = 5
Output: [0,1,1,2,1,2]
Explanation:
0 -->; 0
1 -->; 1
2 -->; 10
3 -->; 11
4 -->; 100
5 -->; 101
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= n <;= 10<sup>5</sup>`


<br /> <br />
<br />**Follow up:**<br />

* It is very easy to come up with a solution with a runtime of `O(n log n)`. Can you do it in linear time `O(n)` and possibly in a single pass?

* Can you do it without using any built-in function (i.e., like `__builtin_popcount` in C++)?