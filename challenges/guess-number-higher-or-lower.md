# 374. Guess Number Higher or Lower

<br />We are playing the Guess Game. The game is as follows:<br />
<br />I pick a number from `1` to `n`. You have to guess which number I picked.<br />
<br />Every time you guess wrong, I will tell you whether the number I picked is higher or lower than your guess.<br />
<br />You call a pre-defined API `int guess(int num)`, which returns three possible results:<br />

* `-1`: Your guess is higher than the number I picked (i.e. `num >; pick`).

* `1`: Your guess is lower than the number I picked (i.e. `num <; pick`).

* `0`: your guess is equal to the number I picked (i.e. `num == pick`).


<br />Return <em>the number that I picked</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 10, pick = 6
Output: 6
```
<br />**Example 2:**<br />
```
Input: n = 1, pick = 1
Output: 1
```
<br />**Example 3:**<br />
```
Input: n = 2, pick = 1
Output: 1
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 2<sup>31</sup> - 1`

* `1 <;= pick <;= n`