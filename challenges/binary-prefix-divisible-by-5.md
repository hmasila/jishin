# 1018. Binary Prefix Divisible By 5

<br />You are given a binary array `nums` (**0-indexed**).<br />
<br />We define `x<sub>i</sub>` as the number whose binary representation is the subarray `nums[0..i]` (from most-significant-bit to least-significant-bit).<br />

* For example, if `nums = [1,0,1]`, then `x<sub>0</sub> = 1`, `x<sub>1</sub> = 2`, and `x<sub>2</sub> = 5`.


<br />Return <em>an array of booleans </em>`answer`<em> where </em>`answer[i]`<em> is </em>`true`<em> if </em>`x<sub>i</sub>`<em> is divisible by </em>`5`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [0,1,1]
Output: [true,false,false]
Explanation: The input numbers in binary are 0, 01, 011; which are 0, 1, and 3 in base-10.
Only the first number is divisible by 5, so answer[0] is true.
```
<br />**Example 2:**<br />
```
Input: nums = [1,1,1]
Output: [false,false,false]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 10<sup>5</sup>`

* `nums[i]` is either `0` or `1`.