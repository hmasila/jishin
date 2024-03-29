# 1332. Remove Palindromic Subsequences

<br />You are given a string `s` consisting **only** of letters `'a'` and `'b'`. In a single step you can remove one **palindromic subsequence** from `s`.<br />
<br />Return <em>the **minimum** number of steps to make the given string empty</em>.<br />
<br />A string is a **subsequence** of a given string if it is generated by deleting some characters of a given string without changing its order. Note that a subsequence does **not** necessarily need to be contiguous.<br />
<br />A string is called **palindrome** if is one that reads the same backward as well as forward.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "ababa"
Output: 1
Explanation: s is already a palindrome, so its entirety can be removed in a single step.
```
<br />**Example 2:**<br />
```
Input: s = "abb"
Output: 2
Explanation: "<u>a</u>bb" ->; "<u>bb</u>" ->; "". 
Remove palindromic subsequence "a" then "bb".
```
<br />**Example 3:**<br />
```
Input: s = "baabb"
Output: 2
Explanation: "<u>baa</u>b<u>b</u>" ->; "<u>b</u>" ->; "". 
Remove palindromic subsequence "baab" then "b".
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 1000`

* `s[i]` is either `'a'` or `'b'`.