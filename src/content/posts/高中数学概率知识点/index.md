---
title: 高中数学_概率知识点留档
auther: HighIQ666
published: 2026-04-16
description: "高中数学概率知识点留档。"
pinned: false
tags: [Senior_math]
category: Senior_math
draft: false
---

## 高中数学概率知识点留档

首先感谢我的数学老师

## 一、随机事件的概率

### 1. 基本概念

1. **样本点**：随机试验的每个可能的基本结果
2. **样本空间**：全体样本点的集合
3. **写出样本空间的步骤**：
    1° 设事件，数字化  
    2° 列出所有样本点（列举、列表、树状图，也可由排列组合算出）
4. **事件分类**：
    - 必然事件：$P=1$
    - 不可能事件：$P=0$
    - 随机事件
5. **频数、频率、概率的关系**：
    $\text{频率}=\frac{\text{频数}}{\text{总数}}$，频率是概率的近似值，概率是频率的稳定值（频率的稳定性）
6. **基本事件**：只包含一个样本点的事件
7. 随机试验满足：
   1. 可重复
   2. 结果均可知
   3. 恰好出现一种结果

### 2. 事件的关系与运算

| 关系/运算 | 定义 | 符号表示 |
| :--- | :--- | :--- |
| 包含关系 | $A$发生则$B$一定发生 | $A \subseteq B$ |
| 并（和）事件 | $A$、$B$至少有一个发生 | $A \cup B$（$A+B$） |
| 交（积）事件 | $A$、$B$同时发生 | $A \cap B$（$AB$） |
| 互斥事件 | $A$、$B$不能同时发生 | $A \cap B = \varnothing$ |
| 对立事件 | $A$、$B$在任何一次试验中**有且仅有一个**发生 | $A \cap B = \varnothing$，$A \cup B = \Omega$ |

### 3. 核心概率公式

1. 若$A$与$B$互斥，则：
    $$P(A \cup B) = P(A) + P(B)$$
2. 若$A$与$B$对立，则：
    $$P(A) + P(B) = 1$$
3. 若$A,B$是同一个随机试验中的两个事件，则：
    $$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$
4. 若$A \subseteq B$，则$P(A) \leq P(B)$（概率的单调性）
    证明：$A \subseteq B \Rightarrow n(A) \leq n(B) \Rightarrow P(A) \leq P(B)$

---

## 二、古典概型

1. **古典概型的特点**：有限性、等可能性
2. **计算公式**：
    $$P(A) = \frac{n(A)}{n(\Omega)}$$
3. **常用求解方法**：列举法、排列组合法
4. **用古典概型求概率的步骤**：
    1° 设事件  
    2° 列举事件$A$和样本空间$\Omega$  
    3° 说明为古典概型  
    4° 计算  
    5° 作答

---

## 三、事件的相互独立性

1. **$A$与$B$独立的定义**：$A$是否发生对$B$的发生的概率没有影响，即
    $$P(AB) = P(A)P(B)$$
2. 若$A,B$独立，则$A$与$\overline{B}$、$\overline{A}$与$B$、$\overline{A}$与$\overline{B}$均独立

:::note
$\because A = AB \cup A\overline{B}$，且$AB$与$A\overline{B}$互斥
$\therefore P(A) = P(AB) + P(A\overline{B})$
$\because A,B$独立，$\therefore P(AB)=P(A)P(B)$
$\therefore P(A) = P(A)P(B) + P(A\overline{B})$
$\Rightarrow P(A\overline{B}) = P(A)(1-P(B))$
$\Rightarrow P(A\overline{B}) = P(A)P(\overline{B})$
$\therefore A$与$\overline{B}$独立
:::

3. **判断$A,B$独立的常用方法**：①常识 ②公式
4. **典型例题**：分别抛掷两枚均匀的硬币，设
    $A=$“第1枚正面向上”，$B=$“第2枚正面向上”，$C=$“2枚向上的面相同”  
    则：  
    $$P(A)=\frac{1}{2},\ P(B)=\frac{1}{2},\ P(C)=\frac{1}{2}$$  
    $$P(AB)=\frac{1}{4},\ P(AC)=\frac{1}{4},\ P(BC)=\frac{1}{4}$$  
    $$P(ABC)=\frac{1}{4}$$
5. $P(B|A)=P(B)$是$A,B$独立的**充要**条件

---

## 四、条件概率

1. **定义**：设$A,B$为两个随机事件，$P(A)>0$，称  
    $$P(B|A) = \frac{P(AB)}{P(A)}$$  
    为$A$发生条件下，$B$发生的条件概率
2. **求条件概率的方法**：公式法、缩小样本空间法
3. 条件概率的性质：
    - 若$B,C$互斥，则$P(B \cup C|A) = P(B|A) + P(C|A)$
    - 若$B$与$\overline{B}$对立，则$P(\overline{B}|A) = 1-P(B|A)$
4. **概率的乘法公式**：
    $$P(AB) = P(A)P(B|A)$$
5. **全概率公式**：
    $$P(B) = \sum_{i=1}^{n} P(A_i)P(B|A_i)$$
6. **贝叶斯公式**：
    $$P(A_i|B) = \frac{P(A_iB)}{P(B)} = \frac{P(A_i)P(B|A_i)}{\sum_{j=1}^{n} P(A_j)P(B|A_j)}$$
7. **三门问题**：核心结论：换门中奖概率更高（换门中奖概率为$\frac{2}{3}$，不换为$\frac{1}{3}$）
