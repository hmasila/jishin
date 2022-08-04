# 1678. Goal Parser Interpretation

<br />You own a **Goal Parser** that can interpret a string `command`. The `command` consists of an alphabet of `"G"`, `"()"` and/or `"(al)"` in some order. The Goal Parser will interpret `"G"` as the string `"G"`, `"()"` as the string `"o"`, and `"(al)"` as the string `"al"`. The interpreted strings are then concatenated in the original order.<br />
<br />Given the string `command`, return <em>the **Goal Parser**'s interpretation of </em>`command`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: command = "G()(al)"
Output: "Goal"
Explanation: The Goal Parser interprets the command as follows:
G ->; G
() ->; o
(al) ->; al
The final concatenated result is "Goal".
```
<br />**Example 2:**<br />
```
Input: command = "G()()()()(al)"
Output: "Gooooal"
```
<br />**Example 3:**<br />
```
Input: command = "(al)G(al)()()G"
Output: "alGalooG"
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= command.length <;= 100`

* `command` consists of `"G"`, `"()"`, and/or `"(al)"` in some order.