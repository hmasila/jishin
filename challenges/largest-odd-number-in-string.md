# 1903. Largest Odd Number in String

<br />You are given a string `num`, representing a large integer. Return <em>the **largest-valued odd** integer (as a string) that is a **non-empty substring** of </em>`num`<em>, or an empty string </em>`""`<em> if no odd integer exists</em>.<br />
<br />A **substring** is a contiguous sequence of characters within a string.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: num = "52"
Output: "5"
Explanation: The only non-empty substrings are "5", "2", and "52". "5" is the only odd number.
```
<br />**Example 2:**<br />
```
Input: num = "4206"
Output: ""
Explanation: There are no odd numbers in "4206".
```
<br />**Example 3:**<br />
```
Input: num = "35427"
Output: "35427"
Explanation: "35427" is already an odd number.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= num.length <;= 10<sup>5</sup>`

* `num` only consists of digits and does not contain any leading zeros.