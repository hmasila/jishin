# 605. Can Place Flowers

<br />You have a long flowerbed in which some of the plots are planted, and some are not. However, flowers cannot be planted in **adjacent** plots.<br />
<br />Given an integer array `flowerbed` containing `0`'s and `1`'s, where `0` means empty and `1` means not empty, and an integer `n`, return `true` <em>if</em> `n` <em>new flowers can be planted in the</em> `flowerbed` <em>without violating the no-adjacent-flowers rule and</em> `false` <em>otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: flowerbed = [1,0,0,0,1], n = 1
Output: true
```<br />**Example 2:**<br />
```
Input: flowerbed = [1,0,0,0,1], n = 2
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= flowerbed.length <;= 2 * 10<sup>4</sup>`

* `flowerbed[i]` is `0` or `1`.

* There are no two adjacent flowers in `flowerbed`.

* `0 <;= n <;= flowerbed.length`