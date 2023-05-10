# 917. Reverse Only Letters

<br />Given a string `s`, reverse the string according to the following rules:<br />

* All the characters that are not English letters remain in the same position.

* All the English letters (lowercase or uppercase) should be reversed.


<br />Return `s`<em> after reversing it</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "ab-cd"
Output: "dc-ba"
```<br />**Example 2:**<br />
```
Input: s = "a-bC-dEf-ghIj"
Output: "j-Ih-gfE-dCba"
```<br />**Example 3:**<br />
```
Input: s = "Test1ng-Leet=code-Q!"
Output: "Qedo1ct-eeLg=ntse-T!"
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 100`

* `s` consists of characters with ASCII values in the range `[33, 122]`.

* `s` does not contain `'\"'` or `'\\'`.