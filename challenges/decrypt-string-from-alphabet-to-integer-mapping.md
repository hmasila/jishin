# 1309. Decrypt String from Alphabet to Integer Mapping

<br />You are given a string `s` formed by digits and `'#'`. We want to map `s` to English lowercase characters as follows:<br />

* Characters (`'a'` to `'i'`) are represented by (`'1'` to `'9'`) respectively.

* Characters (`'j'` to `'z'`) are represented by (`'10#'` to `'26#'`) respectively.


<br />Return <em>the string formed after mapping</em>.<br />
<br />The test cases are generated so that a unique mapping will always exist.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "10#11#12"
Output: "jkab"
Explanation: "j" ->; "10#" , "k" ->; "11#" , "a" ->; "1" , "b" ->; "2".
```
<br />**Example 2:**<br />
```
Input: s = "1326#"
Output: "acz"
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 1000`

* `s` consists of digits and the `'#'` letter.

* `s` will be a valid string such that mapping is always possible.