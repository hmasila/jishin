# 1389. Create Target Array in the Given Order

<br />Given two arrays of integers `nums` and `index`. Your task is to create <em>target</em> array under the following rules:<br />

* Initially <em>target</em> array is empty.

* From left to right read nums[i] and index[i], insert at index `index[i]` the value `nums[i]` in <em>target</em> array.

* Repeat the previous step until there are no elements to read in `nums` and `index.`


<br />Return the <em>target</em> array.<br />
<br />It is guaranteed that the insertion operations will be valid.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: nums = [0,1,2,3,4], index = [0,1,2,2,1]
Output: [0,4,1,3,2]
Explanation:
nums       index     target
0            0        [0]
1            1        [0,1]
2            2        [0,1,2]
3            2        [0,1,3,2]
4            1        [0,4,1,3,2]
```
<br />**Example 2:**<br />
```
Input: nums = [1,2,3,4,0], index = [0,1,2,3,0]
Output: [0,1,2,3,4]
Explanation:
nums       index     target
1            0        [1]
2            1        [1,2]
3            2        [1,2,3]
4            3        [1,2,3,4]
0            0        [0,1,2,3,4]
```
<br />**Example 3:**<br />
```
Input: nums = [1], index = [0]
Output: [1]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= nums.length, index.length <;= 100`

* `nums.length == index.length`

* `0 <;= nums[i] <;= 100`

* `0 <;= index[i] <;= i`