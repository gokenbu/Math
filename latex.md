## Latex 数学公式
---
#### 1. 基本知识

- 命令后加{...}表示命令的作用域

```
a^x+y \neq a^{x+y}
```


$$
a^x+y \neq a^{x+y}
$$


#### 2.常用字符

* 不等号\neq, 空格\qquad, 圆点\cdot, 三圆点\cdots, 箭头\leftarrow, \rightarrow


$$
\neq \qquad \cdot \qquad \cdots \qquad \leftarrow \qquad \rightarrow
$$

- 小写希腊字母
![](/images/greek_lower.JPG)

- 大写希腊字母
![](/images/greek_upper.JPG)

#### 3.格式

* 分数（fraction）\frac{...}{...}


  $$
  X=\frac{a+b}{c-d}
  $$

* 上标^,下标\_,平方根\sqrt，方根\sqrt\[n\]


$$
A^x+B_y=\sqrt{C^z+D} \cdot \sqrt[3]{E-F}
$$


* 上画线\overline, 下画线\underline, 水平大括号\overbrace及\underbrace


$$
\overline{m+n} \qquad \underline{m+n} \qquad 
\overbrace{ a+b+\cdots+z }^{26} \qquad \underbrace{ a+b+\cdots+z }_{26}
$$


* 向量\vec,\overrightarrow,\overleftarrow


  $$
  \vec a\quad \overrightarrow{AB} \quad \overleftarrow{AB}
  $$

* 积分（integral）\int，求和（sum）\sum，乘积运算（product）\prod


$$
\int_{0}^{\frac{\pi}{2}} \qquad
\sum_{i=1}^{n} \qquad
\prod_\epsilon
$$


* 数组

```
\mathbf{X} = \left( \begin{array}{ccc} x_{11} & x_{12} & \ldots \\ x_{21} & x_{22} & \ldots \\ \vdots & \vdots & \ddots
\end{array} \right)\qquad \left(\begin{array}{c|c} 1 & 2 \\ \hline 3 & 4 \end{array}\right)

```


$$
\mathbf{X} =
\left( \begin{array}{ccc}
x_{11} & x_{12} & \ldots \\
x_{21} & x_{22} & \ldots \\
\vdots & \vdots & \ddots
\end{array} \right)
\qquad

\left(\begin{array}{c|c}
1 & 2 \\
\hline
3 & 4
\end{array}\right)
$$




#### 9.数学符号表
- 数学模式重音符
![](/images/accent.JPG)


### Latex基础

#### 空白

空格和制表符空白均SPACE，每行开始的空白字符将被忽略，单个的回车符被视为一空格。

#### 特殊字符

\# $ % ^ & \_ { } ~

使用这些字符时，可在前面加上反斜线

```
\# \$ \% \^{} \& \_ \{ \} \~{}
```

使用'\'则需要输入

```
$$\backslash$$
```

#### 命令

* 以一反斜线'\'开始，加上只包含字母字符命令名组成。命令名后的空格符、数字或其它非字母字符标志该命令的结束。
* 由一反斜线和一特殊字符组成 

许多命令需要一个参数并用一对大括号{ }将其括起来置于命令名称的后面。也有一些命令支持用方括号\[ \]表示可选参数。

```cpp
XXX
```

#### 注释

百分号字符%后的该行文本，分行符以及下一行开始的空白字符将被忽略。

