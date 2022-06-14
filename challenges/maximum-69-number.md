# 1323. Maximum 69 Number

<br />You are given a positive integer `num` consisting only of digits `6` and `9`.<br />
<br />Return <em>the maximum number you can get by changing **at most** one digit (</em>`6`<em> becomes </em>`9`<em>, and </em>`9`<em> becomes </em>`6`<em>)</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: num = 9669
Output: 9969
Explanation: 
Changing the first digit results in 6669.
Changing the second digit results in 9969.
Changing the third digit results in 9699.
Changing the fourth digit results in 9666.
The maximum number is 9969.
```
<br />**Example 2:**<br />
```
Input: num = 9996
Output: 9999
Explanation: Changing the last digit 6 to 9 results in the maximum number.
```
<br />**Example 3:**<br />
```
Input: num = 9999
Output: 9999
Explanation: It is better not to apply any change.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= num <;= 10<sup>4</sup>`

* `num` consists of only `6` and `9` digits.