# 645. Set Mismatch

<br />You have a set of integers `s`, which originally contains all the numbers from `1` to `n`. Unfortunately, due to some error, one of the numbers in `s` got duplicated to another number in the set, which results in **repetition of one** number and **loss of another** number.<br />
<br />You are given an integer array `nums` representing the data status of this set after the error.<br />
<br />Find the number that occurs twice and the number that is missing and return <em>them in the form of an array</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1,2,2,4]
Output: [2,3]
```<br />**Example 2:**<br />
```
Input: nums = [1,1]
Output: [1,2]
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= nums.length <;= 10<sup>4</sup>`

* `1 <;= nums[i] <;= 10<sup>4</sup>`