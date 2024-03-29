# 575. Distribute Candies

<br />Alice has `n` candies, where the `i<sup>th</sup>` candy is of type `candyType[i]`. Alice noticed that she started to gain weight, so she visited a doctor.<br />
<br />The doctor advised Alice to only eat `n / 2` of the candies she has (`n` is always even). Alice likes her candies very much, and she wants to eat the maximum number of different types of candies while still following the doctor's advice.<br />
<br />Given the integer array `candyType` of length `n`, return <em>the **maximum** number of different types of candies she can eat if she only eats </em>`n / 2`<em> of them</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: candyType = [1,1,2,2,3,3]
Output: 3
Explanation: Alice can only eat 6 / 2 = 3 candies. Since there are only 3 types, she can eat one of each type.
```
<br />**Example 2:**<br />
```
Input: candyType = [1,1,2,3]
Output: 2
Explanation: Alice can only eat 4 / 2 = 2 candies. Whether she eats types [1,2], [1,3], or [2,3], she still can only eat 2 different types.
```
<br />**Example 3:**<br />
```
Input: candyType = [6,6,6,6]
Output: 1
Explanation: Alice can only eat 4 / 2 = 2 candies. Even though she can eat 2 candies, she only has 1 type.
```
<br /> <br />
<br />**Constraints:**<br />

* `n == candyType.length`

* `2 <;= n <;= 10<sup>4</sup>`

* `n` is even.

* `-10<sup>5</sup> <;= candyType[i] <;= 10<sup>5</sup>`