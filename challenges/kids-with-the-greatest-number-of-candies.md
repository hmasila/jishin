# 1431. Kids With the Greatest Number of Candies

<br />There are `n` kids with candies. You are given an integer array `candies`, where each `candies[i]` represents the number of candies the `i<sup>th</sup>` kid has, and an integer `extraCandies`, denoting the number of extra candies that you have.<br />
<br />Return <em>a boolean array </em>`result`<em> of length </em>`n`<em>, where </em>`result[i]`<em> is </em>`true`<em> if, after giving the </em>`i<sup>th</sup>`<em> kid all the </em>`extraCandies`<em>, they will have the **greatest** number of candies among all the kids</em><em>, or </em>`false`<em> otherwise</em>.<br />
<br />Note that **multiple** kids can have the **greatest** number of candies.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: candies = [2,3,5,1,3], extraCandies = 3
Output: [true,true,true,false,true] 
Explanation: If you give all extraCandies to:
- Kid 1, they will have 2 + 3 = 5 candies, which is the greatest among the kids.
- Kid 2, they will have 3 + 3 = 6 candies, which is the greatest among the kids.
- Kid 3, they will have 5 + 3 = 8 candies, which is the greatest among the kids.
- Kid 4, they will have 1 + 3 = 4 candies, which is not the greatest among the kids.
- Kid 5, they will have 3 + 3 = 6 candies, which is the greatest among the kids.
```
<br />**Example 2:**<br />
```
Input: candies = [4,2,1,1,2], extraCandies = 1
Output: [true,false,false,false,false] 
Explanation: There is only 1 extra candy.
Kid 1 will always have the greatest number of candies, even if a different kid is given the extra candy.
```
<br />**Example 3:**<br />
```
Input: candies = [12,1,12], extraCandies = 10
Output: [true,false,true]
```
<br /> <br />
<br />**Constraints:**<br />

* `n == candies.length`

* `2 <;= n <;= 100`

* `1 <;= candies[i] <;= 100`

* `1 <;= extraCandies <;= 50`