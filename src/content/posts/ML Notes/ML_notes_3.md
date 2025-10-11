---
title: DL learning notes -- Part 3
published: 2025-10-06
description: 'ML learning notes-Part 3, references: LeeDL-Tutorial'
image: ''
tags: [PyTorch, DL, ML]
category: 'Notes'
draft: false 
lang: ''
---

# 参考

> 李宏毅 深度学习教程：[LeeDL-Tutorial](https://github.com/datawhalechina/leedl-tutorial)

# Chapter 12-17

## 对抗攻击

**动机**：攻击者可以通过小幅修改原有图像，使模型输出完全不一样的结果，产生安全隐患

**攻击目的**

- 无目标攻击：在图片中加入噪声，希望网络的输出与真实情况不同；计算损失函数时，要求损失越大越好
- 有目标攻击：在网络输出与真实情况差别越大越好的基础上，还要求网络输出与目标输出越近越好
- 黑盒/白盒攻击、对抗攻击训练公式推导：略

