# 1021. Remove Outermost Parentheses

<br />A valid parentheses string is either empty `""`, `"(" + A + ")"`, or `A + B`, where `A` and `B` are valid parentheses strings, and `+` represents string concatenation.<br />

* For example, `""`, `"()"`, `"(())()"`, and `"(()(()))"` are all valid parentheses strings.


<br />A valid parentheses string `s` is primitive if it is nonempty, and there does not exist a way to split it into `s = A + B`, with `A` and `B` nonempty valid parentheses strings.<br />
<br />Given a valid parentheses string `s`, consider its primitive decomposition: `s = P<sub>1</sub> + P<sub>2</sub> + ... + P<sub>k</sub>`, where `P<sub>i</sub>` are primitive valid parentheses strings.<br />
<br />Return `s` <em>after removing the outermost parentheses of every primitive string in the primitive decomposition of </em>`s`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "(()())(())"
Output: "()()()"
Explanation: 
The input string is "(()())(())", with primitive decomposition "(()())" + "(())".
After removing outer parentheses of each part, this is "()()" + "()" = "()()()".
```
<br />**Example 2:**<br />
```
Input: s = "(()())(())(()(()))"
Output: "()()()()(())"
Explanation: 
The input string is "(()())(())(()(()))", with primitive decomposition "(()())" + "(())" + "(()(()))".
After removing outer parentheses of each part, this is "()()" + "()" + "()(())" = "()()()()(())".
```
<br />**Example 3:**<br />
```
Input: s = "()()"
Output: ""
Explanation: 
The input string is "()()", with primitive decomposition "()" + "()".
After removing outer parentheses of each part, this is "" + "" = "".
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 10<sup>5</sup>`

* `s[i]` is either `'('` or `')'`.

* `s` is a valid parentheses string.