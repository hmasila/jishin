# 989. Add to Array-Form of Integer

<br />The **array-form** of an integer `num` is an array representing its digits in left to right order.<br />

* For example, for `num = 1321`, the array form is `[1,3,2,1]`.


<br />Given `num`, the **array-form** of an integer, and an integer `k`, return <em>the **array-form** of the integer</em> `num + k`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: num = [1,2,0,0], k = 34
Output: [1,2,3,4]
Explanation: 1200 + 34 = 1234
```
<br />**Example 2:**<br />
```
Input: num = [2,7,4], k = 181
Output: [4,5,5]
Explanation: 274 + 181 = 455
```
<br />**Example 3:**<br />
```
Input: num = [2,1,5], k = 806
Output: [1,0,2,1]
Explanation: 215 + 806 = 1021
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= num.length <;= 10<sup>4</sup>`

* `0 <;= num[i] <;= 9`

* `num` does not contain any leading zeros except for the zero itself.

* `1 <;= k <;= 10<sup>4</sup>`