# 1773. Count Items Matching a Rule

<br />You are given an array `items`, where each `items[i] = [type<sub>i</sub>, color<sub>i</sub>, name<sub>i</sub>]` describes the type, color, and name of the `i<sup>th</sup>` item. You are also given a rule represented by two strings, `ruleKey` and `ruleValue`.<br />
<br />The `i<sup>th</sup>` item is said to match the rule if **one** of the following is true:<br />

* `ruleKey == "type"` and `ruleValue == type<sub>i</sub>`.

* `ruleKey == "color"` and `ruleValue == color<sub>i</sub>`.

* `ruleKey == "name"` and `ruleValue == name<sub>i</sub>`.


<br />Return <em>the number of items that match the given rule</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: items = [["phone","blue","pixel"],["computer","silver","lenovo"],["phone","gold","iphone"]], ruleKey = "color", ruleValue = "silver"
Output: 1
Explanation: There is only one item matching the given rule, which is ["computer","silver","lenovo"].
```
<br />**Example 2:**<br />
```
Input: items = [["phone","blue","pixel"],["computer","silver","phone"],["phone","gold","iphone"]], ruleKey = "type", ruleValue = "phone"
Output: 2
Explanation: There are only two items matching the given rule, which are ["phone","blue","pixel"] and ["phone","gold","iphone"]. Note that the item ["computer","silver","phone"] does not match.```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= items.length <;= 10<sup>4</sup>`

* `1 <;= type<sub>i</sub>.length, color<sub>i</sub>.length, name<sub>i</sub>.length, ruleValue.length <;= 10`

* `ruleKey` is equal to either `"type"`, `"color"`, or `"name"`.

* All strings consist only of lowercase letters.