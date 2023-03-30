# 771. Jewels and Stones

<br />You're given strings `jewels` representing the types of stones that are jewels, and `stones` representing the stones you have. Each character in `stones` is a type of stone you have. You want to know how many of the stones you have are also jewels.<br />
<br />Letters are case sensitive, so `"a"` is considered a different type of stone from `"A"`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: jewels = "aA", stones = "aAAbbbb"
Output: 3
```<br />**Example 2:**<br />
```
Input: jewels = "z", stones = "ZZ"
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= jewels.length, stones.length <;= 50`

* `jewels` and `stones` consist of only English letters.

* All the characters of `jewels` are **unique**.