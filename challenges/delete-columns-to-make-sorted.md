# 944. Delete Columns to Make Sorted

<br />You are given an array of `n` strings `strs`, all of the same length.<br />
<br />The strings can be arranged such that there is one on each line, making a grid.<br />

* For example, `strs = ["abc", "bce", "cae"]` can be arranged as follows:


```abc
bce
cae
```
<br />You want to **delete** the columns that are **not sorted lexicographically**. In the above example (**0-indexed**), columns 0 (`'a'`, `'b'`, `'c'`) and 2 (`'c'`, `'e'`, `'e'`) are sorted, while column 1 (`'b'`, `'c'`, `'a'`) is not, so you would delete column 1.<br />
<br />Return <em>the number of columns that you will delete</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: strs = ["cba","daf","ghi"]
Output: 1
Explanation: The grid looks as follows:
  cba
  daf
  ghi
Columns 0 and 2 are sorted, but column 1 is not, so you only need to delete 1 column.
```
<br />**Example 2:**<br />
```
Input: strs = ["a","b"]
Output: 0
Explanation: The grid looks as follows:
  a
  b
Column 0 is the only column and is sorted, so you will not delete any columns.
```
<br />**Example 3:**<br />
```
Input: strs = ["zyx","wvu","tsr"]
Output: 3
Explanation: The grid looks as follows:
  zyx
  wvu
  tsr
All 3 columns are not sorted, so you will delete all 3.
```
<br /> <br />
<br />**Constraints:**<br />

* `n == strs.length`

* `1 <;= n <;= 100`

* `1 <;= strs[i].length <;= 1000`

* `strs[i]` consists of lowercase English letters.