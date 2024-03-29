# 两数之和

## 题目 

给定一个整数数组 nums 和一个目标值 target，请你在该数组中找出和为目标值的那 两个 整数，并返回他们的数组下标。

你可以假设每种输入只会对应一个答案。但是，你不能重复利用这个数组中同样的元素。

示例:

```bash
给定 nums = [2, 7, 11, 15], target = 9

因为 nums[0] + nums[1] = 2 + 7 = 9
所以返回 [0, 1]
```

## 思路

1. 暴力法，两层循环遍历数组，找到和为target的两个数， 时间复杂度O(n^2)

2. 哈希表，存入num -> index的映射，然后遍历数组，查找target - num是否在哈希表中， 时间复杂度O(n)


## 参考

[LeetCode](https://leetcode-cn.com/problems/two-sum/)
