# 832. Flipping an Image

<br />Given an `n x n` binary matrix `image`, flip the image **horizontally**, then invert it, and return <em>the resulting image</em>.<br />
<br />To flip an image horizontally means that each row of the image is reversed.<br />

* For example, flipping `[1,1,0]` horizontally results in `[0,1,1]`.


<br />To invert an image means that each `0` is replaced by `1`, and each `1` is replaced by `0`.<br />

* For example, inverting `[0,1,1]` results in `[1,0,0]`.


<br /> <br />
<br />**Example 1:**<br />
```
Input: image = [[1,1,0],[1,0,1],[0,0,0]]
Output: [[1,0,0],[0,1,0],[1,1,1]]
Explanation: First reverse each row: [[0,1,1],[1,0,1],[0,0,0]].
Then, invert the image: [[1,0,0],[0,1,0],[1,1,1]]
```
<br />**Example 2:**<br />
```
Input: image = [[1,1,0,0],[1,0,0,1],[0,1,1,1],[1,0,1,0]]
Output: [[1,1,0,0],[0,1,1,0],[0,0,0,1],[1,0,1,0]]
Explanation: First reverse each row: [[0,0,1,1],[1,0,0,1],[1,1,1,0],[0,1,0,1]].
Then invert the image: [[1,1,0,0],[0,1,1,0],[0,0,0,1],[1,0,1,0]]
```
<br /> <br />
<br />**Constraints:**<br />

* `n == image.length`

* `n == image[i].length`

* `1 <;= n <;= 20`

* `images[i][j]` is either `0` or `1`.