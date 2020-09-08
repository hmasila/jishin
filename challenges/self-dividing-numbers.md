# 728. Self Dividing Numbers

<br />A **self-dividing number** is a number that is divisible by every digit it contains.<br />

* For example, `128` is **a self-dividing number** because `128 % 1 == 0`, `128 % 2 == 0`, and `128 % 8 == 0`.


<br />A **self-dividing number** is not allowed to contain the digit zero.<br />
<br />Given two integers `left` and `right`, return <em>a list of all the **self-dividing numbers** in the range</em> `[left, right]`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: left = 1, right = 22
Output: [1,2,3,4,5,6,7,8,9,11,12,15,22]
```<br />**Example 2:**<br />
```
Input: left = 47, right = 85
Output: [48,55,66,77]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= left <;= right <;= 10<sup>4</sup>`