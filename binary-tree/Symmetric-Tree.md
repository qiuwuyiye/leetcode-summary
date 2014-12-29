# Symmetric Tree

题目来源：[Symmetric Tree](https://oj.leetcode.com/problems/symmetric-tree/)

>
	Given a binary tree, check whether it is a mirror of itself (ie, symmetric around its center).
	
解题思路：
左节点的左子树 ＝ 右节点的由子树。 
解题方法跟[same tree](./same-tree.html)差不多。

### 递归

```cpp
	
	bool isSymmetric(TreeNode* node1, TreeNode* node2)
```

### 迭代

```cpp

	bool isSymmetric(TreeNode *root)

 

