## Latex

---

### 数学公式

#### 1. 基本知识

命令后加{...}表示命令的作用域

```
a^x+y \neq a^{x+y}
```


$$
a^x+y \neq a^{x+y}
$$


#### 2.希腊字母

```
\alpha,\beta, \gamma,\delta, \Gamma,\Delta
```


$$
 \alpha,\beta, \gamma,\delta, \Gamma,\Delta
$$


#### 3.符号
- 不等号\neq， 空格\qquad，省略号\cdots


$$

$$


### 4.格式
- 指数^,下标\_,平方根\sqrt，方根\sqrt\[n\]


$$
A_x+B_y+C^z \neq \sqrt{D+E} * \sqrt[3]{F-G}
$$


- 上画线\overline，下画线\underline


$$
\overline{m+n} \qquad \underline{m+n}
$$

- 上、下方水平大括号: \overbrace 和\underbrace

$$
\overbrace{ a+b+\cdots+z }^{26} \qquad \underbrace{ a+b+\cdots+z }_{26}
$$


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

