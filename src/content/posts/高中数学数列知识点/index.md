---
title: 高中数学_数列知识点留档
auther: HighIQ666
published: 2026-02-05
description: "高中数学数列知识点留档。"
pinned: false
tags: [Senior_math]
category: Senior_math
draft: false
---

## 高中数学数列知识点留档

首先感谢我的数学老师

### 等差数列

#### 等差数列定义

若数列$\{a_n\}$满足$a_n-a_{n-1}=d$（常数）/$a_{n+1}-a_n=d$ $(n\ge2)$，则称数列$\{a_n\}$为等差数列

#### 判断等差数列的方法

- ①定义法
- ②等差中项法

#### 证明等差数列的方法

- ①定义法
- ②等差中项法
- ③通项公式法
- ④前n项和公式法

#### 等差数列通项公式

$$
a_n=a_1+(n-1)d
$$

或

$$
a_n=pn+q\quad(p=d,a_1=p+q)
$$

:::note
等差数列的通项公式是形式上的一次函数
:::

推论：

$a_n=a_m+(n-m)d$；$k=\frac{a_n-a_m}{n-m}$，$a_{n+k}=a_n+kd$

#### 等差数列前$n$项和

##### 等差数列前$n$项和公式

$$
S_n=na_1+\frac{n(n-1)}{2}d=\frac{n(a_1+a_n)}{2}
$$

倒序相加法

:::note
类似梯形面积公式
:::

##### 等差数列前$n$项和公式变形

$$
S_n=\frac{d}{2}n^2+\left(a_1-\frac{d}{2}\right)n
$$

也可记为 $S_n=An^2+Bn$（其中 $A=\frac{d}{2},\;B=a_1-\frac{d}{2}$）

:::note
等差数列前$n$项和是关于$n$的形式上的二次函数，且不含常数项
:::

- 当 $d \neq 0$ 时，$S_n$ 可看作二次函数 $y=\frac{d}{2}x^2+\left(a_1-\frac{d}{2}\right)x$（$x \in \mathbb{R}$）在 $x=n$ 处的函数值
- 当 $d < 0$ 时，$S_n$ 是开口向下的抛物线，$S_n$ 有最大值
- 当 $d > 0$ 时，$S_n$ 是开口向上的抛物线，$S_n$ 有最小值

**应用**：求等差数列$S_n$的最值

- 方法1：利用$a_n$，找正负分界
- 方法2：利用二次函数求最值，注意$n \in \mathbb{N}_+$

#### 等差中项

- A是a、b的等差中项，则$A=\frac{a+b}{2}$；任意两个数都有等差中项，且唯一
- 任意两个数都有等差中项，且唯一

推论：

- 若$m+n=p+q\ (m,n,p,q\in N_+)$，则$a_m+a_n=a_p+a_q$
- 若$m+n=2p\ (m,n,p\in N_+)$，则$a_m+a_n=2a_p$

:::note
两边项数要一致
:::

#### 单调性

设$\{a_n\}$的公差为$d$，则

$$
d>0 \Leftrightarrow \{a_n\}\text{为递增数列} \\
d<0 \Leftrightarrow \{a_n\}\text{为递减数列} \\
d=0 \Leftrightarrow \{a_n\}\text{为常数列}
$$

#### 等差数列结论

1. 数列的通项$a_n$与前n项和$S_n$的关系

$$
a_n=
\begin{cases}
S_n\ (n=1)\\
S_n-S_{n-1}\ (n\ge2)
\end{cases}
$$

（数列$\{a_n\}$的前n项和为$S_n=a_1+a_2+\dots+a_n$）

已知$S_n$与$a_n$（或$S_n$与$n$）的关系，求$a_n$

- ①$n=1$,$a_1=S_1$
- ②$n\ge2$,$a_n=S_n-S_{n-1}$
- ③验证$n=1$
- ④下结论

2. 数列：$a_1,a_2,\dots,a_n$与集合$\{a_1,a_2,\dots,a_n\}$区别

数列各项有序，而集合元素无序

3. 下标等差项等差：$a_n$ 等差， $a_k,a_{k+m},a_{k+2m},\dots$ 等差，公差 $d'=md$

4. 等差数列前n项和$S_n,\{\frac{S_n}{n}\}$也是等差数列,$\frac{S_n}{n}=a_1+(n-1)\frac{d}{2}$，公差为$\frac{d}{2}$

5. 片段和等差：等差数列$\{a_n\}$(公差d)中前n项和为$S_n$,则$S_m,S_{2m}-S_m,S_{3m}-S_{2m}$成等差数列,公差为$m^2d$

6. 等差数列前2n-1项和公式：$S_{2n-1}=(2n-1)a_n$, $S_n=na_{\frac{n+1}{2}}$，$S_{2n}=n（a_n+a_{n+1}）$

7. 设等差数列$\{a_n\}$的前n项和为$S_n$，等差数列$\{b_n\}$的前n项和为$T_n$

（1）$\frac{S_n}{T_n}=\frac{a_1+a_n}{b_1+b_n}$；
（2）$\frac{a_n}{b_n}=\frac{2a_n}{2b_n}=\frac{a_1+a_{2n-1}}{b_1+b_{2n-1}}=\frac{S_{2n-1}}{T_{2n-1}}$

8. 已知$\frac{S_n}{T_n}=\frac{an+b}{cn+d}$ 则$\frac{a_m}{b_n}=\frac{S_{2m-1}}{T_{2n-1}}$

证：设$S'_n=kn(an+b)$ $T'_n=kn(cn+d)$
$\frac{a_m}{b_n}=\frac{2a_m}{2b_n}=\frac{a_1+a_{2m-1}}{b_1+b_{2n-1}}=\frac{(\frac{(2m-1)(a_1+a_{2m-1})}{2})(2n-1)}{(\frac{(2n-1)(b_1+b_{2n-1})}{2})(2m-1)}=\frac{(S'_{2m-1})(2n-1)}{(T'_{2n-1})(2m-1)}=\frac{k(2m-1)[a(2m-1)+b](2n-1)}{k(2n-1)[c(2n-1)+d](2m-1)}=\frac{a(2m-1)+b}{c(2n-1)+d}=\frac{S_{2m-1}}{T_{2n-1}}$

9. 等差数列的奇偶项

（1）若项数为2n，则$S_{偶}-S_{奇}=nd$，$\frac{S_{奇}}{S_{偶}}=\frac{a_n}{a_{n+1}}$

$S_{偶}=a_2+a_4+a_6+\dots+a_{2n}$  
$S_{奇}=a_1+a_3+a_5+\dots+a_{2n-1}$  
$\Rightarrow S_{偶}-S_{奇}=nd$

$S_{奇}=\frac{n(a_1+a_{2n-1})}{2}=na_n$  
$S_{偶}=\frac{n(a_2+a_{2n})}{2}=na_{n+1}$  
$\Rightarrow \frac{S_{奇}}{S_{偶}}=\frac{a_n}{a_{n+1}}$

（2）若项数为$2n-1$，则$S_{奇}-S_{偶}=a_n$，$\frac{S_{奇}}{S_{偶}}=\frac{n}{n-1}$

$S_{奇}=\frac{n(a_1+a_{2n-1})}{2}=na_n$  
$S_{偶}=\frac{(n-1)(a_2+a_{2n-2})}{2}=(n-1)a_n$  
$\Rightarrow S_{奇}-S_{偶}=a_n$  
$\frac{S_{奇}}{S_{偶}}=\frac{n}{n-1}$

10. 等差数列$\{a_n\}$与$\{b_n\}$中，$a_n=a_1+(n-1)d_1$与$b_n=b_1+(n-1)d_2,\{a_n\}$与$\{b_n\}$的共同项构成一个新的等差数列，其公差为$d_1$与$d_2$最小公倍数

11.  等差数列$\{a_n\}$前$n$项和为$S_n$，若 $a_1>0,\;d<0,\;a_m=0$，记

$$
T_n=|a_1|+|a_2|+\dots+|a_n|
$$

则

$$
T_n=
\begin{cases}
S_n & (1 \le n \le m) \\
-S_n+2S_m & (n \ge m+1)
\end{cases}
$$

12. 等差数列$\{a_n\}$公差$d$，$S_{m+n}=S_m+S_n+mnd=\frac{(m+n)(S_m-S_n)}{m-n}$

推论：若$S_m=n$,$S_n=m$,则$S_{m+n}=-(m-n)$

### 等比数列

#### 等比数列定义

若数列$\{a_n\}$满足 $\frac{a_{n+1}}{a_n}=q$（$q \neq 0$ 为常数）/ $\frac{a_n}{a_{n-1}}=q\ (n \ge 2)$ ，则称$\{a_n\}$为等比数列

#### 判断等比数列的方法

- ①定义法
- ②等比中项法

#### 等比数列通项公式

$$
a_n=a_1 q^{n-1}\;(n \in \mathbb{N}_+)
$$

或

$$
a_n=\left(\frac{a_1}{q}\right) q^n\;(n \in \mathbb{N}_+)
$$

推论：

$$
a_n=a_m q^{n-m},\quad
\frac{a_n}{a_m}=q^{n-m},\quad
a_{n+k}=a_n q^k
$$

#### 等比数列$\{a_n\}$单调性

- $a_1>0,q>1$ 或 $a_1<0,0<q<1 \implies \{a_n\}$为递增数列
- $a_1>0,0<q<1$ 或 $a_1<0,q>1 \implies \{a_n\}$为递减数列
- $q=1 \implies \{a_n\}$为常数列
- $q<0 \implies \{a_n\}$为摆动数列

- $q>0$ 时数列各项正负**相同**
- $q<0$ 时数列各项正负**相间**
- 不论正负，等比数列奇数项正负相同，偶数项正负相同

#### 等比数列前$n$项和

##### 等比数列前$n$项和公式

- 当 $q \neq 1$ 时：$S_n=\frac{a_1(1-q^n)}{1-q}=\frac{a_1-a_n q}{1-q}$
- 当 $q = 1$ 时：$S_n=n a_1$

:::warning
求等比数列前$n$项和一定要考虑$q$是否为1
:::

##### 等比数列前$n$项和公式变形

$S_n=A-A q^n\;(q \neq 1)$

其中 $A=\frac{a_1}{1-q}$

#### 等比中项

若$G$是$a$、$b$的等比中项，则

$G=\pm\sqrt{ab}$

:::warning
$a$、$b$必须同号  
同号的两个数才有等比中项，且有2个
:::

推论：

- 若 $m+n=p+q$（$m,n,p,q \in \mathbb{N}_+$），则$a_m \cdot a_n=a_p \cdot a_q$
- 若$\{a_n\}$是等比数列，$p,q,r$为正整数且 $p+q=2r$，则$a_p \cdot a_q=a_r^2$

#### 等比数列性质

1. 若$\{a_n\}$与$\{b_n\}$是等比数列，公比分别为$q$、$p$，则
$\{c a_n\},\;\{a_n^2\},\;\left\{\frac{1}{a_n}\right\},\;\{a_n^r\}\;(r \in \mathbb{Z}),\;\{a_n b_n\}$
也是等比数列（$c \neq 0$），公比依次为
$q,\;q^2,\;\frac{1}{q},\;q^r,\;pq$

2. 下标等差项等比：$a_n$ 等比， $a_k,a_{k+m},a_{k+2m},\dots$ 等比，公比 $q'=mq$

3. 片段和等比：若等比数列$\{a_n\}$的前$n$项和为$S_n$，则$S_k,\;S_{2k}-S_k,\;S_{3k}-S_{2k},\;\dots$成等比数列（各项不为0），公比为$q^k$

4. 等比数列奇偶项

- 等比数列$\{a_n\}$项数为偶数，则$\frac{S_{偶}}{S_{奇}}=q$
- 等比数列$\{a_n\}$项数为奇数，则$\frac{S_{奇}-a_1}{S_{偶}}=q$

5. 若等比数列$\{a_n\}$的前$n$项和为$S_n$，则$S_{m+n}=S_m+q^m S_n=S_n+q^n S_m$（$q=1$时也成立）

**证明**：
$$
\begin{align*}
S_{m+n}&=a_1+a_2+\dots+a_m+a_{m+1}+a_{m+2}+\dots+a_{m+n}\\
&=S_m+a_{m+1}+a_{m+2}+\dots+a_{m+n}\\
&=S_m+a_1 q^m+a_2 q^m+\dots+a_n q^m\\
&=S_m+q^m(a_1+a_2+\dots+a_n)\\
&=S_m+q^m S_n
\end{align*}
$$

当$S_n = A - Aq^n$时，$S_n - S_m = A(q^m - q^n)$，其中$A=\frac{a_1}{1-q}$

6. 既是等差数列又是等比数列的数列是**非零**常数列

### 数列综合

#### 结论

1. 数列$\{(-1)^n\}$和$\{(-1)^{n+1}\}$表示正负相间的变化规律（调和数列）
2. 若等差数列$\{a_n\}$满足$a_n = a_1 + (n-1)d$，则数列$\{b^{a_n}\}$是等比数列，公比为$b^d$
3. 若等比数列$\{a_n\}$满足$a_n = a_1 q^{n-1}$且$a_n>0$，则数列$\{\log_b a_n\}$是等差数列，公差为$\log_b q$
4. 若数列$\{a_n\}$满足$a_{n+1} = q a_n + d$（$qd \neq 0,q \neq 1$），可构造等比数列$\{a_n + t\}$，满足$a_{n+1} + t = q(a_n + t)$，其中$t=\frac{d}{q-1}$

#### 数学归纳法

一般地，证明一个与正整数$n$有关的命题$P(n)$，可按下列步骤进行：

（1）**归纳奠基**：证明当$n = n_0$（$n_0 \in \mathbb{N}^*$）时命题$P(n_0)$成立；

（2）**归纳递推**：以“当$n = k$（$k \in \mathbb{N}^*$，$k \ge n_0$）时命题$P(k)$成立”为条件，推出“当$n = k + 1$时命题$P(k+1)$也成立”。

只要完成这两个步骤，就可以断定命题对从$n_0$开始的所有正整数$n$都成立，这种证明方法称为数学归纳法。

#### 数列单调性常用方法

- 作差法（邻项差分法，比较$a_{n+1} - a_n$与0的大小）
- 利用函数单调性法

:::note
数列的定义域是正整数集或其子集
:::

#### 平方和公式

$$
1^2 + 2^2 + 3^2 + \dots + n^2 = \frac{1}{6}n(n+1)(2n+1)
$$

#### 立方和公式

$$
1^3 + 2^3 + 3^3 + \dots + n^3 = \left[\frac{1}{2}n(n+1)\right]^2
$$

#### 斐波那契数列

若数列$\{F_n\}$满足$F_1=1,\;F_2=1,\;F_n = F_{n-1} + F_{n-2}$（$n \ge 3,\;n \in \mathbb{N}^*$），则$\{F_n\}$称为斐波那契数列。

其通项公式为：

$$
F_n = \frac{1}{\sqrt{5}}\left[\left(\frac{\sqrt{5}+1}{2}\right)^n - \left(\frac{1-\sqrt{5}}{2}\right)^n\right]
$$

#### 等比数列所有项的和（$|q| < 1$时）

$$
S=\frac{a_1}{1-q}
$$

#### 根式有理化公式

$$
\frac{1}{\sqrt{n+1}+\sqrt{n}} = \sqrt{n+1} - \sqrt{n}
$$

#### 不等式关系

$$
\frac{1}{n-1} - \frac{1}{n} > \frac{1}{n^2} > \frac{1}{n+1} - \frac{1}{n}
$$

#### 重要极限公式

$$
\lim_{n \to \infty} \left(1+\frac{1}{n}\right)^n = e
$$

### 数列部分常用方法

归纳法、迭代法、并项求和法、分组求和法、裂项相消法、错位相减法、累加法、累乘法、倒序相加法、构造等差等比数列。

#### 一、求通项的方法

1.  **观察法（适应选填）**

    例子：
    - $1,3,5,7,9,\dots \implies a_n=2n-1$
    - $1,2,4,8,16,\dots \implies a_n=2^{n-1}$
    - $1,4,9,16,25,\dots \implies a_n=n^2$
    - $1,-1,1,-1,\dots \implies a_n=(-1)^{n+1}$
    - $9,99,999,\dots \implies a_n=10^n-1$
    - $1,11,111,\dots \implies a_n=\frac{10^n-1}{9}$
    - $1,0,1,0,\dots \implies a_n=\frac{(-1)^{n+1}+1}{2}$
    - $0.9,0.99,0.999,\dots \implies a_n=1-\left(\frac{1}{10}\right)^n$
    数列通项公式不一定存在，存在不一定唯一

2.  **累加法（$a_{n+1}-a_n=f(n)$）**

    ① 当 $n\ge2$ 时：

    $$
    \begin{align*}
    a_2-a_1 &= f(1) \\
    a_3-a_2 &= f(2) \\
    &\vdots \\
    a_n-a_{n-1} &= f(n-1)
    \end{align*}
    $$

    将 $n-1$ 个式子相加得：

    $$
    a_n-a_1 = f(1)+\dots+f(n-1) \implies a_n=\sum_{i=1}^{n-1}f(i)+a_1
    $$

    ② 验证 $n=1$

    ③ 下结论

3.  **累乘法（$\frac{a_{n+1}}{a_n}=f(n)$）**

4.  **$S_n$与$a_n$转化**

5.  **作商法**

    已知 $a_1a_2\cdots a_n=f(n)$ 求 $a_n$

    $$
    a_n=\begin{cases}
    f(1) & n=1 \\
    \frac{f(n)}{f(n-1)} & n\ge2
    \end{cases}
    $$

6.  **倒数法（$a_{n+1}=\frac{pa_n}{ka_n+p}$）**

    $$
    \frac{1}{a_{n+1}}=\frac{ka_n+p}{pa_n}=\frac{k}{p}+\frac{1}{a_n} \implies \frac{1}{a_{n+1}}-\frac{1}{a_n}=\frac{k}{p}
    $$

7.  **构造等比数列法（$a_{n+1}=pa_n+q$）**

    设 $a_{n+1}+\lambda=p(a_n+\lambda)$，则 $p\lambda-\lambda=q \implies \lambda=\frac{q}{p-1}$

#### 二、其他构造方法

1.  **含幂的构造等差数列**

    ① $a_{n+1}=pa_n+p^n$ 求 $a_n$

    $$
    \frac{a_{n+1}}{p^{n+1}}=\frac{a_n}{p^n}+\frac{1}{p} \implies \frac{a_{n+1}}{p^{n+1}}-\frac{a_n}{p^n}=\frac{1}{p}
    $$

    ② $a_{n+1}=pa_n+q^n$ 求 $a_n$

    $$
    \frac{a_{n+1}}{q^{n+1}}=\frac{p}{q}\cdot\frac{a_n}{q^n}+\frac{1}{q}
    $$

    （同方法7）

2.  **换元法构造新数列**

    已知 $a_{n+1}=pa_n+qa_{n-1}\ (n\ge2)$

    设 $(a_{n+1}-xa_n)=y(a_n-xa_{n-1})$，则

    $$
    a_{n+1}=(x+y)a_n-xy a_{n-1}
    $$

    解得方程组：

    $$
    \begin{cases}x+y=p \\ -xy=q\end{cases}
    $$

3.  **取对数**

    已知 $a_{n+1}=pa_n^k\ (a_n>0,p>0,k\neq1)$

    $$
    \log_c a_{n+1}=\log_c p + k\log_c a_n
    $$

    （同方法7）

#### 三、数列求和（按求项先研究通项）

1.  **公式法**

2.  **分组求和**

3.  **倒序相加**（倒序后对应项的和为定值）

4.  **错位相减**（仅适用于等比数列求和公式 $S_n=\frac{a_1-a_n q}{1-q}$ 相关形式）

5.  **裂项相消**

    常用裂项公式：

    $$
    \begin{align*}
    \frac{1}{n(n+1)}&=\frac{1}{n}-\frac{1}{n+1} \\
    \frac{1}{n(n+k)}&=\frac{1}{k}\left(\frac{1}{n}-\frac{1}{n+k}\right) \\
    \frac{1}{n(n+1)(n+2)}&=\frac{1}{2}\left[\frac{1}{n(n+1)}-\frac{1}{(n+1)(n+2)}\right] \\
    \log_a \frac{n+1}{n}&=\log_a(n+1)-\log_a n \\
    \frac{1}{\sqrt{n}+\sqrt{n+1}}&=\sqrt{n+1}-\sqrt{n} \\
    \frac{2^n}{(2^n-1)(2^{n+1}-1)}&=\frac{1}{2^n-1}-\frac{1}{2^{n+1}-1} \\
    \frac{1}{n\cdot n!}&=\frac{1}{n!}-\frac{1}{(n+1)!}
    \end{align*}
    $$
