### Laplace Transform

#### 1. 定义

$$
L[f(t)] = F(s) = \int_{0}^{\infty}f(t)e^{-st}dt
\qquad \qquad (s=\sigma + j\omega)
$$

$$
L^{-1}[F(s)]=f(t) = \frac{1}{2{\pi}j} \int_{c-j\infty}^{c+j\infty}F(s)e^{st}ds 
$$

#### 2. 常用变换


$$
1  \qquad\rightarrow\qquad    \frac{1}{s}
$$

$$
t    \qquad\rightarrow\qquad    \frac{1}{s^2}
$$

$$
t^2    \qquad\rightarrow\qquad    \frac{2}{s^3}
$$

$$
e^{at}    \qquad\rightarrow\qquad    \frac{1}{s+a}
$$

$$
\sin\omega t    \qquad\rightarrow\qquad    \frac{\omega}{s^2+\omega^2}
$$

$$
\cos\omega t \qquad\rightarrow\qquad \frac{s}{s^2+\omega^2}
$$


$$
\frac{di(t)}{dt}
 \qquad\rightarrow\qquad sI(s) - i(0)
$$

$$
\int{i(t)dt}\qquad\rightarrow\qquad \frac{I(s)}{s} + \frac{q(0)}{s} 
$$

#### 3. 基本性质

$$
线性定理\qquad\qquad
L[af(t)]=aF(s)\qquad\qquad
L[f_1(t)±f_2(t)]=F_1(s)±F_2(s)
$$

$$
微分定理\qquad\qquad
L[af(t)]=aF(s)\qquad\qquad
L[f_1(t)±f_2(t)]=F_1(s)±F_2(s)
$$



#### 4. 常用逆变换





XX




