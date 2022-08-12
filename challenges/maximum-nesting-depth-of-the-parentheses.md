# 1614. Maximum Nesting Depth of the Parentheses

<br />A string is a **valid parentheses string** (denoted **VPS**) if it meets one of the following:<br />

* It is an empty string `""`, or a single character not equal to `"("` or `")"`,

* It can be written as `AB` (`A` concatenated with `B`), where `A` and `B` are **VPS**'s, or

* It can be written as `(A)`, where `A` is a **VPS**.


<br />We can similarly define the **nesting depth** `depth(S)` of any VPS `S` as follows:<br />

* `depth("") = 0`

* `depth(C) = 0`, where `C` is a string with a single character not equal to `"("` or `")"`.

* `depth(A + B) = max(depth(A), depth(B))`, where `A` and `B` are **VPS**'s.

* `depth("(" + A + ")") = 1 + depth(A)`, where `A` is a **VPS**.


<br />For example, `""`, `"()()"`, and `"()(()())"` are **VPS**'s (with nesting depths 0, 1, and 2), and `")("` and `"(()"` are not **VPS**'s.<br />
<br />Given a **VPS** represented as string `s`, return <em>the **nesting depth** of </em>`s`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "(1+(2*3)+((<u>8</u>)/4))+1"
Output: 3
Explanation: Digit 8 is inside of 3 nested parentheses in the string.
```
<br />**Example 2:**<br />
```
Input: s = "(1)+((2))+(((<u>3</u>)))"
Output: 3
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 100`

* `s` consists of digits `0-9` and characters `'+'`, `'-'`, `'*'`, `'/'`, `'('`, and `')'`.

* It is guaranteed that parentheses expression `s` is a **VPS**.