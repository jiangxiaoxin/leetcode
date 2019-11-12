# Leetcode

## 项目说明

- 分 3 个版本，**html**、**node**、**vscode**

- 3 个版本都支持**es6**语法

- html 和 node 版本会监听文件变化，自动编译，重新执行

- vscode 是直接在 vscode 里`F5`执行，可以在编辑器里断点调试

- html 有个问题，一旦代码有问题，中间造成死循环，那就恶心了，关不掉，刷新也不行

- node 也有问题，断点不容易

- vscode 看似完美，也有问题，每次启动太慢了

## 解体技巧

- 递归

通常递归要涉及到大量的栈的操作（出栈，入栈），相对来说性能指标不是很好，可转为迭代法。

典型例子就是 fibonacci 序列问题，递归解法最浅显易懂，但耗时严重。一种优化方式就是开辟数组空间，记录下已经计算过的值，省得每次都是重新计算。或者从头开始计算，一直计算到指定的 n

- 迭代
- 大问题拆解小问题，然后合并结果
- 反证法

## 题目列表

### 简单

- 217.存在重复元素

### 中等

### 困难

- 13.罗马数字转整数
- 14.最长公共前缀
- 70.爬楼梯
- 100 相同的树
- 101.对称二叉树
- 104.二叉树的最大深度
- 108.一个按照升序排列的有序数组，转换为一棵高度平衡二叉搜索树。
- 111.二叉树的最小深度
- 203.移除链表元素
- 237.删除链表中的节点
- 26.删除排序数组中的重复项
- 27.移除元素
- 136.只出现一次的数字
- 344.反转字符串
- 1137.第 N 个泰波那契数
- 1247.交换字符使得字符串相同
