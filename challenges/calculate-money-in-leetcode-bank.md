# 1716. Calculate Money in Leetcode Bank

<br />Hercy wants to save money for his first car. He puts money in the Leetcode bank **every day**.<br />
<br />He starts by putting in `$1` on Monday, the first day. Every day from Tuesday to Sunday, he will put in `$1` more than the day before. On every subsequent Monday, he will put in `$1` more than the **previous Monday**.<span style="display:none"> </span><br />
<br />Given `n`, return <em>the total amount of money he will have in the Leetcode bank at the end of the </em>`n<sup>th</sup>`<em> day.</em><br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 4
Output: 10
Explanation: After the 4<sup>th</sup> day, the total is 1 + 2 + 3 + 4 = 10.
```
<br />**Example 2:**<br />
```
Input: n = 10
Output: 37
Explanation: After the 10<sup>th</sup> day, the total is (1 + 2 + 3 + 4 + 5 + 6 + 7) + (2 + 3 + 4) = 37. Notice that on the 2<sup>nd</sup> Monday, Hercy only puts in $2.
```
<br />**Example 3:**<br />
```
Input: n = 20
Output: 96
Explanation: After the 20<sup>th</sup> day, the total is (1 + 2 + 3 + 4 + 5 + 6 + 7) + (2 + 3 + 4 + 5 + 6 + 7 + 8) + (3 + 4 + 5 + 6 + 7 + 8) = 96.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 1000`