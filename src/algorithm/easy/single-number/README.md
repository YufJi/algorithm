# 只出现一次的数字

## 描述

给定一个非空整数数组，**除了一个元素只出现一次之外，其余每个元素均出现两次**。找出那个只出现了一次的元素。

## 思路

1. 哈希表，当时不满足题目要求，因为需要额外的空间。

2. 位运算，使用异或运算，异或运算满足交换律和结合律，所以可以直接对整个数组进行异或运算，最后的结果就是只出现一次的元素。（特别注意题目中重复元素只出现2次）

## 参考

- [LeetCode](https://leetcode-cn.com/problems/single-number/) 
