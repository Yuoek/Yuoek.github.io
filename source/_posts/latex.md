---
title:  Latex
date:   2024-08-01
lang: zh
tags:   latex
categories: latex
---


要用 NVIM 来写日记啦，坚持坚持再坚持呀！数学公式 Latex。

<!--more-->

Latex 数学常用的公式
以下是一些在 LaTeX 中常用的数学公式示例：

1. 基本数学运算符
    - 加法：$a + b$ 显示为 $a + b$
    - 减法：$a - b$ 显示为 $a - b$
    - 乘法：$a \cdot b$ 显示为 $a \cdot b$ ，也可以使用 $a\times b$ 显示为 $a\times b$
    - 除法：$\frac{a}{b}$ 显示为 $\frac{a}{b}$

2. 上标和下标
    - 上标：$a^{b}$ 显示为 $a^{b}$
    - 下标：$a_{b}$ 显示为 $a_{b}$

3. 分数
    - 普通分数：$\frac{numerator}{denominator}$ ，例如 $\frac{3}{4}$ 显示为 $\frac{3}{4}$

4. 平方根
    - $\sqrt{x}$ 显示为 $\sqrt{x}$
    - 立方根：$\sqrt[3]{x}$ 显示为 $\sqrt[3]{x}$

5. 求和与积分
    - 求和：$\sum_{i=1}^{n} a_i$ 显示为 $\sum_{i=1}^{n} a_i$
    - 积分：$\int_{a}^{b} f(x) dx$ 显示为 $\int_{a}^{b} f(x) dx$

6. 方程组
    - 使用 \begin{cases}... \end{cases} 来表示方程组，例如：
    latex
    \begin{cases}
    x + y = 3 \\
    x - y = 1
    \end{cases}
    
    显示为
    \begin{cases}
    x + y = 3 \\
    x - y = 1
    \end{cases}

7. 矩阵
    - 使用 \begin{pmatrix}... \end{pmatrix} 来表示矩阵，例如：
    latex
    \begin{pmatrix}
    1 & 2 \\
    3 & 4
    \end{pmatrix}
    
    显示为
    $\begin{pmatrix}
    1 & 2 \\
    3 & 4
    \end{pmatrix}$

## 1
$$
\iint\limits_D\left(\dfrac{\partial Q}{\partial x}-\dfrac{\partial P}{\partial y}\right){\rm d}x{\rm d}y=\oint\limits_LP{\rm d}x+Q{\rm d}y
$$


## 2
$$
f\left(
\left[
\dfrac{1+\{x,y\}}{\left(\dfrac{x}{y}+\dfrac{y}{x}\right)(u+1)}+a
\right]
^{\dfrac{3}{2}}
\right)
\tag{行标}
$$

## 3
$$
\left\langle q\middle\|\dfrac{\dfrac{x}{y}}{\dfrac{u}{v}}\middle|p\right\rangle
$$

## 4
\require{cancel}\begin{array}{r1}
\verb|y+\cancel{x}|&y+\cancel{x}\\
\verb|y+\cancel{y+x}|&y+\cancel{y+x}\\
\verb|y+\bcancel{x}|&y+\bcancel{x}\\
\verb|y+\xcancel{x}|&y+\xcancel{x}\\
\verb|y+\cancelto{0}{x}|&y+\cancelto{0}{x}\\
\verb+\frac{1\cancel9}{\cancel95}=\frac15+&\frac{1\cancel9}{\cancel95}=\frac15\\
\end{array}


## 5
\begin{align}
\sqrt{37}=\sqrt{\dfrac{73^2-1}{12^2}}\\
&=\sqrt{\dfrac{73^2}{12^2}\cdot\dfrac{73^2-1}{73^2}}\\
&=\sqrt{\dfrac{73^2}{12^2}}\sqrt{\dfrac{73^2-1}{73^2}}\notag\\
&=\dfrac{73}{12}\sqrt{1-\dfrac{1}{73^2}}\\
\approx\dfrac{73}{12}\left(1-\dfrac{1}{2\cdot73^2}\right)\label{A}
\end{align}

## 6
\begin{align*}
v+m&=0&\text{Given}\tag1\\
-w&=-w+0&\text{additive identity}\tag2\\
-w+0&=-w+(v+w)&\text{equations $(1)$ and $(2)$}
\end{align*}

## 7
$$
\require{cancel}\begin{array}{r1}
\verb|y+\cancel{x}|&y+\cancel{x}\\
\verb|y+\cancel{y+x}|&y+\cancel{y+x}\\
\verb|y+\bcancel{x}|&y+\bcancel{x}\\
\verb|y+\xcancel{x}|&y+\xcancel{x}\\
\verb|y+\cancelto{0}{x}|&y+\cancelto{0}{x}\\
\verb+\frac{1\cancel9}{\cancel95}=\frac15+&\frac{1\cancel9}{\cancel95}=\frac15\\
\end{array}
$$

## 8
$$
\begin{matrix}
1&x&x^2\\
1&y&y^2\\
1&z&z^2\\
\end{matrix}
$$

## 9
\begin{align*}
v+m&=0&\text{Given}\tag1\\
-w&=-w+0&\text{additive identity}\tag2\\
-w+0&=-w+(v+w)&\text{equations $(1)$ and $(2)$}
\end{align*}
