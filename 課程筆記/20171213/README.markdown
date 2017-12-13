# 20171213 筆記
## 回顧
![photo 0941]()

* $$ F = q (\overrightarrow{V} \times \overrightarrow{B}) $$
* $$ \mid \overrightarrow{F} \mid = qVB \sin \theta $$
* $$ \overrightarrow{F} = I(\overrightarrow{l} \times \overrightarrow{B}) $$
* 磁偶級距：$$ \overrightarrow{\tau} = I(\overrightarrow{A} \times \overrightarrow{B}) $$

## 必歐—沙伐(?)定律<br>Biot-Savart Law
* 流動中的電流本身可以產生一個磁場（跟由外在磁場對流動的電流產生的磁力的概念不同）
* $$ d \overrightarrow{B} = k_m \frac{I d \overrightarrow{s} \times \hat{r}}{r^2} $$
	* ![image0950]()
	* $$ d \overrightarrow{s} $$：導線長度的單位
	* $$ \overrightarrow{r} $$：導線某段（$$ d \overrightarrow{s} $$）對觀測點的位移(?)向量
	* 觀測點離導線距離越大感受到的磁場越少
	* $$ \hat{r} $$ ：大小為1
* $$ k_m = \frac{\mu_0}{4 \pi} $$：真空磁導率
* $$ \mu_0 = 4 \pi \times 10^{-7} {^{T \cdot m}}/_A $$
* $$k_m = 10^{-7}$$

### 尋找 $$ \overrightarrow{B} $$ 在長直導線上電流 $$ I $$
![image1000]()

* $$ d B = \frac{\mu_0}{4\pi}I\frac{d\overrightarrow{s} \times \hat{r}}{} $$
* $$ d \overrightarrow{S} \times \hat{r} = \hat{i} dx x \hat{r} = dx \sin \theta \hat{out} $$
* （依賴內積、外積公式）
* $$ \begin{case}
r = a \cos \theta \\
x = -a \cot \theta
\end{case} \to dx = +a \csc^2 \theta d \theta $$
* $$ dB = \frac{\mu_0 I}{4\pi} + \frac{a \csc^2\theta \sin \theta d \theta}{a^2 \csc^2 \theta} $$
* $$ B = \frac{\mu_0 I}{4\pi} \frac{\sin\theta d \theta}{a} $$
* $$ B = \frac{\mu_0 I}{4\pi} \frac{1}{a} \int^{\theta_2}{\theta_1} = \frac{\mu_0 I}{4\pia} (-\cos \theta) \int^{\theta_2}_{\theta_1} \\
\frac{\mu_0 I}{4\pi a} (\cos \theta_1 - \cos \theta_2)\\
B = \frac{\mu_0}{4 \pi}\frac{I}{a} (\cos \theta_1 - \cos \theta_2)  $$
* 一條相當長的導線（$$ \infnt $$ ) $$ \theta_1 \to 0 $$、 $$ \theta_2 \to \pi $$  
$$ B = \frac{\mu_0}{4\pi}\frac{I}{a}(\cos 0 - \cos \pi) = \frac{\mu_0}{4\pi} \frac{I}{a} \times 2 = \frac{\mu_0}{2\pi}\frac{I}{a} $$
* $$ B = \frac{\mu_0}{2\pi}\frac{I}{a} $$
* 注意：長直導線的磁場線呈現以導線為中心的同心圓

![image1037](image1037.png)

* current $$ I $$ 流出紙面

### 例：尋找 $$ B $$ 長直導線有 $$ 1 A $$，離這導線有 1 公尺的距離
![image1047](image1047.png)

* (misses)

### 電流圓線圈引起的 $$ \overrightarrow{B} $$
![image1050](image1050.png)

* $$ \begin{align*}
dB = \frac{\mu_0}{4\pi} I \frac{d\overrightarrow{s} \times \hat{r}}{r^2} \\
&= \frac{\mu_0}{I}
\end{align*} $$

## Misc.
### Hall Effect
{%youtube wpAA3qeOYiI %}