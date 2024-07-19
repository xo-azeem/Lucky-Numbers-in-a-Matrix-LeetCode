# Lucky Numbers in a Matrix

LeetCode Q # 1380.

Given an m x n matrix of distinct numbers, return all lucky numbers in the matrix in any order.

A lucky number is an element of the matrix such that it is the minimum element in its row and maximum in its column.

Example 1:

> Input: matrix = [[3,7,8],[9,11,13],[15,16,17]]</br>
> Output: [15]</br>
> Explanation: 15 is the only lucky number since it is the minimum in its row and the maximum in its column.

Example 2:

> Input: matrix = [[1,10,4,2],[9,3,8,7],[15,16,17,12]]</br>
> Output: [12]</br>
> Explanation: 12 is the only lucky number since it is the minimum in its row and the maximum in its column.

Example 3:

> Input: matrix = [[7,8],[1,2]]</br>
> Output: [7]</br>
> Explanation: 7 is the only lucky number since it is the minimum in its row and the maximum in its column.

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/49470d17-ee5d-48ee-b6a2-8fd9a1ec84e2)

  Time complexity: O(n * m).</br>Space complexity: O(n + m).
</div>
