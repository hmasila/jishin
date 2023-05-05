# 908. Smallest Range I

<br />You are given an integer array `nums` and an integer `k`.<br />
<br />In one operation, you can choose any index `i` where `0 <;= i <; nums.length` and change `nums[i]` to `nums[i] + x` where `x` is an integer from the range `[-k, k]`. You can apply this operation **at most once** for each index `i`.<br />
<br />The **score** of `nums` is the difference between the maximum and minimum elements in `nums`.<br />
<br />Return <em>the minimum **score** of </em>`nums`<em> after applying the mentioned operation at most once for each index in it</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [1], k = 0
Output: 0
Explanation: The score is max(nums) - min(nums) = 1 - 1 = 0.
```
<br />**Example 2:**<br />
```
Input: nums = [0,10], k = 2
Output: 6
Explanation: Change nums to be [2, 8]. The score is max(nums) - min(nums) = 8 - 2 = 6.
```
<br />**Example 3:**<br />
```
Input: nums = [1,3,6], k = 3
Output: 0
Explanation: Change nums to be [4, 4, 4]. The score is max(nums) - min(nums) = 4 - 4 = 0.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length <;= 10<sup>4</sup>`

* `0 <;= nums[i] <;= 10<sup>4</sup>`

* `0 <;= k <;= 10<sup>4</sup>`