# 2017/9/27 上課筆記
## 微積分簡介
* \(
y = x^3 \\
\frac{dy}{dx} = \frac{dx^3}{dx} = 3x^2 \\
\frac{dx}{dt} = nAt^{n-1}
\)

### 例題：假設一個質點的位置可由下列方程式表示：$$ x = 4-27t + t^3 $$ 其中 \( x\) 的單位為公尺，\(t\)的單位為秒。
#### (a) 此質點的 \( V(t) \) 和 \( a(t) \) 的函數式？
\(
V(t) = \frac{dx(t)}{dt} = -27 +  3t^2 \\
a(t) = \frac{dV(t)}{dt} = 6t
\)

#### (b) 何時 \( V = 0 \) ？
\(
V(t) = 0 = -27 + 3t^2\\
t = \pm3 sec.
\)

#### (c) 從 0~4 秒的平均速度為何？\(t = 4 sec \) 時的瞬時速度與加速度？
\(
V_{0~4} = \frac{x(4) - x(0)}{4-0} = \frac{-40 - 4}{4} = -11 ^{m}/_{s}
\)

\(
V(4) = -27 + 3 \times 16 = 21 ^{m}/_{s}
\)

### 積分的概念
* \(
\frac{dF(x)}{dx} = f(x)\\
\int dF(x) = \int f(x)dx
\)
* \(
	\int x^n dx = \frac{x^{n+1}}{n + 1}
\)
* \(
	\int x \cdot dx = \\
	\int \frac{1}{x}dx = \ln x
\)
	* \( \ln  = log_e = 2.71828... \)
* \( \begin{align*}
	\int^b_a f(x)dx &= F(b) - F(a) \\
	&= F(x) |^b_a
\end{align*} \)
* 例： \( y = 2x^2 \)  
\( \begin{align*}
\int^3_2 2x^2dx &= \frac{2}{3}x^3 |^3_2\\
&= \frac{2}{3}(3^3 - 2^3)
\end{align*}\)

![照片]()

## 自由落體<br>Free Falling
* 鉛直軸作等加速度運動
* 四個相關公式（每個都少一種元素）
	* \( \begin{align*}
 V_f &= V_i + at （缺 X_f X_i） \\
 X_f - x_i &= V_i t + \frac{1}{a}at^2 （缺 V_f）\\
 X_f - x+i &= \frac{1}{2}(V_i + V_f)t （缺 a ）\\
 V_f^2 &= V_i^2 + 2a(x_f - x_i) （缺 t）
\end{align*} \)

![照片1039]()

## 拋體運動
* 在拋體運動，水平運動與鉛直運動各自獨立
* 假設：
	1. 自由落體的加速度 \( g \) 在此運動中相同，方向向下
	2. 忽略空氣阻力的作用
* 拋體移動的路徑稱為軌道，拋體軌道永遠是拋物線的形式<br>The path of a projectile（拋體） is called its trajectary（軌道）  
It is always a Parabola（拋物線）

![照片1045]()
	* 初速為 \(V_i\)
	* 自原點： \( 
cos{\theta{i}} = \frac{V_{x_i}}{V_i}\\
sin{\theta{i}} = \frac{V_{y_i}}{V_i}\\
初速 V_{x_i} = V_i \cos{\theta{i}}\\
V_{y_i} = V_i sin{\theta{i}}\\
V_xf = V_xi = V_i \cos{\theta{i}}\\
V_yf = V_yi - gt = V_i \sin{\theta} - gt
\)

\( \begin{align*}
x_f = V_xi t = V_i \cos{\theta_i} t
y_f &= V_yi t - \frac{1}{2} gt^2\\
&= V_ii \sin{t} = \frac{1}{2}gt^2
\end{align*}\)

![照片1056]()
![照片1058]()

* 最大高度(maximum height)：  
\( \begin{align*}
0 &= V_i ai \theta_i - gt\\
t &= \frac{V_i \sin{\theta_i}}{g}
\end{align*} \\
k = y_i &= V_i \sin{\theta_i}(V_i \frac{R_I \theta_i}{g}) - \frac{1}{2} g (V_i \frac{}{} (missed)

\)

### horizontal range of a projetile
* \( \begin{align*}
R = V_i \cos{\theta_i}(2t) &= V_i \cos{\theta_i} - 2 \frac{V_i\sin{\theta_i}}{g}\\
&= V_i^2 \frac{2 \sin{\theta_i}\cos{\theta_i}}{g} \\
&= \frac{{V_i}^2}{}(missed)
\end{align*}\)
![照片1103]()

* ![圖1104]()
	* 仰角 45 \deg 射程最遠

## 等速率圓周運動<br>Uniform Circular Motion
* 以半徑為 \( r \) 圓形的路徑上以等速率 \( V \) 運動，仍有加速度 ]（註：向心加速度）

### 向心加速度<br>Centripidal Acceleration
* \( a_c = \frac{V^2}{r} \)
* ![圖1126]()
	* 一開始的速度標示為 \( V_i \)，結束前的速度為 \( V_f \)
	* \( \overrightarrow{V_i} \) 與 \( \overrightarrow{V_f} \) 的夾角一樣是 \( \theta \)（原因：軸轉 \( 2 \pi \) 度時其緣之切線也轉 \( 2 \pi \) 度
	* 將 \( \overrightarrow{V_i} \) 與 \( \overrightarrow{V_f} \) 起點對齊可組成一相似三角形
	* 可得 \( \frac{\Delta \overrightarrow{r}}{r} = \frac{\Delta \overrightarrow{r}}{V} \to \Delta\overrightarrow{V} = \frac{V}{r} \Delta \overrightarrow{r} \to \frac{\Delta \overrightarrow{V}}{\Delta t} = \frac{V}{r} \frac{\Delta (missed) }{} \)
	* ![照片1133]()

* 週期<br>period：質點以等速率在半徑 \(r\) 的圓周運動
	* \( T = \frac{2 \pi r}{V} \\
a = \frac{V^2}{r} \)

* \( \overrightarrow{a} = \overrightarrow{a_t} + \overrightarrow{a_r} \)
	* \( a_t \) ：切線加速度(tangential acceleration) 速率改變
	* 徑向加速度(radial acceleration)：速度向量之方向
		* \( a_r = -a_c = \frac{-V^2}{r}
* ![圖1140]()

## 第 21 章
* (missing)
### 電荷<br>Electric Charges
* 兩種電荷：正電荷，負電荷
* 由 Benjamin Franklin 發現
* 日常生活所見物體：多為電中性
* 同性電荷相斥，異性電荷相吸

### 導體、非導體與半導體
* 導體<br>Conductor
	* 電荷在內可自由移動的物質，如金屬
* 非導體<br>Insulator
	* 也稱為絕緣體
	* 如玻璃
* 半導體<br>Semi-conductor
	* 導電性介於導體和絕緣體之間的物質
	* 如電腦晶片原料的矽(silicon)與鍺(germinite)
* 超導體<br>Super-conductor
	* 完美導體的物質，可允許電荷不電荷不受任何阻礙的移動