# 888. Fair Candy Swap

<br />Alice and Bob have a different total number of candies. You are given two integer arrays `aliceSizes` and `bobSizes` where `aliceSizes[i]` is the number of candies of the `i<sup>th</sup>` box of candy that Alice has and `bobSizes[j]` is the number of candies of the `j<sup>th</sup>` box of candy that Bob has.<br />
<br />Since they are friends, they would like to exchange one candy box each so that after the exchange, they both have the same total amount of candy. The total amount of candy a person has is the sum of the number of candies in each box they have.<br />
<br />Return a<em>n integer array </em>`answer`<em> where </em>`answer[0]`<em> is the number of candies in the box that Alice must exchange, and </em>`answer[1]`<em> is the number of candies in the box that Bob must exchange</em>. If there are multiple answers, you may **return any** one of them. It is guaranteed that at least one answer exists.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: aliceSizes = [1,1], bobSizes = [2,2]
Output: [1,2]
```
<br />**Example 2:**<br />
```
Input: aliceSizes = [1,2], bobSizes = [2,3]
Output: [1,2]
```
<br />**Example 3:**<br />
```
Input: aliceSizes = [2], bobSizes = [1,3]
Output: [2,3]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= aliceSizes.length, bobSizes.length <;= 10<sup>4</sup>`

* `1 <;= aliceSizes[i], bobSizes[j] <;= 10<sup>5</sup>`

* Alice and Bob have a different total number of candies.

* There will be at least one valid answer for the given input.