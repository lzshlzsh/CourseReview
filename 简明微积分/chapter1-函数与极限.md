## 函数与极限
### 数列极限与函数极限
数列
```math
\{a_1,a_2,...,a_n,...\}
```
的极限可用第九章p41的`$\varepsilon$`-`$N$`语言严格定义

如果有一定数`$a$`，对于不管怎么小的正数`$\varepsilon$`，都相应存在一个自然数`$ N = N(\varepsilon)$`（它随`$\varepsilon$`变动），只要`$n>N$`，就有`$|a_n - a| < \varepsilon$`，则说`$\lim_{n \to \infty}a_n = a$`

且可以证明，
- 两个数列各对应项的和、差、积、商组成的数列的极限，分别等于两个数列的极限的和、差、积、商。
- 如果`$a_n \leqslant b_n \leqslant c_n$`，则`$\lim_{n \to \infty}a_n \leqslant \lim_{n \to \infty}b_n \leqslant \lim_{n \to \infty}c_n$`

函数的极限`$\lim_{x \to \infty}f(x) = A$`可证明有类似的性质
- 两个函数的和、差、积、商的极限，分别等于极限的和、差、积、商。
- 夹逼性质：如果`$f(x) \leqslant h(x) \leqslant g(x)$`，且`$\lim_{x \to \infty}f(x) = \lim_{x \to \infty}g(x) = A$`，那么`$\lim_{x \to \infty}h(x) = A$`

### 连续函数
- 定义

    函数`$f(x)$`在`$x=x_0$`处连续，是指
```math
\lim_{x \to x_0}f(x) = f(x_0)
```
- 介值定理

    若$f(t)$在$[a,b]$上连续，$r$是介于$f(a)$与$f(b)$之间的任意数（即$f(a) < r < f(b)$，或者$f(b) < r < f(a)$），则必存在$c \in (a, b)$使得$f(c) = r$。
- 闭区间上的连续函数存在**最大值**和**最小值**
