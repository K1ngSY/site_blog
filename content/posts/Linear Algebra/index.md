+++
date = '2025-10-08T19:12:11-07:00'
draft = false
title = 'Linear Algebra'
description = "Some tips for my Linear Algebra Study"
summary = "Some tips for my Linear Algebra Study"
tags = ["posts"]
+++

# 🧮 行列运算对行列式的影响（Determinant Effects of Row/Column Operations）

## 一、三种基本行运算及其影响

| 操作类型 | 符号表示 | 含义 | 对行列式的影响 |
|:--|:--|:--|:--|
| **交换两行** | `Rᵢ ↔ Rⱼ` | 把第 i 行与第 j 行互换 | 行列式乘以 **−1** |
| **数乘一行** | `Rᵢ → cRᵢ` | 把第 i 行的所有元素乘以常数 c | 行列式乘以 **c** |
| **行加倍操作** | `Rᵢ → Rᵢ + cRⱼ` | 把第 j 行的 c 倍加到第 i 行 | 行列式 **不变** |

> 💡 以上三种操作称为「初等行变换（Elementary Row Operations）」。  
> 对列操作（Column Operations）同理，效果完全对称。

---

## 二、列运算的影响（对称性质）

| 操作类型 | 符号表示 | 含义 | 对行列式的影响 |
|:--|:--|:--|:--|
| **交换两列** | `Cᵢ ↔ Cⱼ` | 把第 i 列与第 j 列互换 | 行列式乘以 **−1** |
| **数乘一列** | `Cᵢ → cCᵢ` | 把第 i 列的所有元素乘以常数 c | 行列式乘以 **c** |
| **列加倍操作** | `Cᵢ → Cᵢ + cCⱼ` | 把第 j 列的 c 倍加到第 i 列 | 行列式 **不变** |

---

## 三、多次交换的符号规律

若矩阵 \(A\) 经过 **k 次行交换**（或列交换）得到矩阵 \(B\)，则：

\[
\det(B) = (-1)^k \det(A)
\]

- 交换 **奇数次** → 行列式乘以 **−1**  
- 交换 **偶数次** → 行列式 **不变**

---

## 四、总结口诀（易记版）

> **“一换变负号，双换又还原；  
> 数乘乘常量，加倍不改变。”**

---

## 五、补充说明

- 交换行或列是 **符号变化操作**。  
- 数乘行或列是 **倍数变化操作**。  
- 加倍操作（把一行加上另一行的倍数）是 **行列式不变操作**。  
- 若两行（或两列）**成比例或相同**，则行列式为 **0**。  
- 若某行（或某列）全为 **0**，行列式也为 **0**。  
- 转置矩阵不改变行列式：  
  \[
  \det(A^T) = \det(A)
  \]

---

📘 **Quick Summary in English**

| Operation | Effect on det(A) |
|:--|:--|
| Swap two rows/columns | × (−1) |
| Multiply a row/column by c | × c |
| Add multiple of one row/column to another | No change |
| k swaps total | × (−1)ᵏ |
| Two identical/proportional rows/columns | det(A) = 0 |
| Aᵀ (Transpose) | det(Aᵀ) = det(A) |

---
