## 定积分
### 定积分的定义
- 黎曼和

    $f(x)$是定义在区间$[a,b]$上的连续函数，以$T$表示用点$a = x_0 < x_1 < ... < x_{n-1} < x_n = b$来分区间$[a,b]$的任意一种分法，作和
    $$
    \sigma = \sum_{i=1}^{n}f(\xi_i) \Delta x_i
    $$
    
    其中$\Delta x_i = x_i - x_{i-1}$，$\xi_i \in [x_{i-1}, x_i]$。
- 定积分

    令$\lambda(T) = \max{\Delta x_i | 1 \le i \le n}$，则
    $$
    I = \lim_{\lambda(T) \to 0} \sigma = 
    \lim_{n \to \infty} \sigma = \int_{a}^{b}f(x)dx
    $$
    
- 性质

    - 线性性质。根据极限的性质，可知线性性质成立（和、差、系数）。
    - 区间可加性。
    - 不等式性质。两条。
    - 积分中值定理。
    $$
    \int_{a}^{b}f(x)dx = f(\xi)(b-a), \quad \xi \in (a,b)
    $$
    
    
    证明：
    1. 若$f(x)$在区间$[a,b]$上为常函数，则结论显然的。否则，
    2. 设$m,\,M$分别为$f(x)$在区间$[a,b]$的最小值和最大值，则
    $$
    \sum_{i=1}^{n}m \Delta x_i <
    \sum_{i=1}^{n}f(\xi_i) \Delta x_i <
    \sum_{i=1}^{n}M \Delta x_i
    $$
    
    因此，
    $$
    m(b-a) <
    \int_{a}^{b}f(x)dx <
    M(b-a)
    $$
    
    $$
    m < 
    \frac{1}{b-a}\int_{a}^{b}f(x)dx <
    M
    $$
    
    根据连续函数的介值定理，存在$\quad \xi \in (a,b)$使得
    $$
    f(\xi) = \frac{1}{b-a}\int_{a}^{b}f(x)dx
    $$
    
    即
    $$
    \int_{a}^{b}f(x)dx = f(\xi)(b-a)
    $$
    
    
