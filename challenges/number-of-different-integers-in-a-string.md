# 1805. Number of Different Integers in a String

<br />You are given a string `word` that consists of digits and lowercase English letters.<br />
<br />You will replace every non-digit character with a space. For example, `"a123bc34d8ef34"` will become `" 123  34 8  34"`. Notice that you are left with some integers that are separated by at least one space: `"123"`, `"34"`, `"8"`, and `"34"`.<br />
<br />Return <em>the number of **different** integers after performing the replacement operations on </em>`word`.<br />
<br />Two integers are considered different if their decimal representations **without any leading zeros** are different.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: word = "a<u>123</u>bc<u>34</u>d<u>8</u>ef<u>34</u>"
Output: 3
**Explanation: **The three different integers are "123", "34", and "8". Notice that "34" is only counted once.
```
<br />**Example 2:**<br />
```
Input: word = "leet<u>1234</u>code<u>234</u>"
Output: 2
```
<br />**Example 3:**<br />
```
Input: word = "a<u>1</u>b<u>01</u>c<u>001</u>"
Output: 1
**Explanation: **The three integers "1", "01", and "001" all represent the same integer because
the leading zeros are ignored when comparing their decimal values.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= word.length <;= 1000`

* `word` consists of digits and lowercase English letters.