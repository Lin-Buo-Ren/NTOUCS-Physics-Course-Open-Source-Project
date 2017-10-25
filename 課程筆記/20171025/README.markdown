# 20171025 筆記
## unknown
* \(
\epsilon_0 \Phi = q_{enc}\\
雙橫線向右箭頭 \epsilon_0 \oint \overrightarrow{E} \cdot d \overrightarrow{A} = q_{enc}
\)
* ![graph0950]()
* \( \begin{align*}
\epsilon_0 (E \cdot A) &= q\\
&= \sigma \cdot A
\end{align*}\)
* \( \begin{align*}
\epsilon_0 E \cancel{A} (missing)
\end{align*}\)	

## 兩平行導體板
* ![graph0955]()
* \( \overrightarrow{E} \cdot \overrightarrow{A} \)
* \( \overrightarrow{E_左} \cdot  \overrightarrow{A_左} + \overrightarrow{E_邊} \cdot \overrightarrow{A_邊} + \overrightarrow{E_右} \cdot \overrightarrow{A_右} \)
* \( \begin{align*}
\epsilon_0 \Phi &= q\\
\epsilon_0 \overrightarrow{E_右} \cdot \overrightarrow{A_右} = \sigma A \\
\epsilon_0 E_右 \cancel{A_右} \cdot 1 = \sigma A \\
\epsilon_0 E_右 = \sigma \\
E_右 = \frac{\sigma}{\epsilon_0}
\end{align*} \)

## 電位
### Preliminaries
#### 保守力<br>Conservative Force
* 若質點在兩點間運動，所作的功與質點所移動的路徑無關而只跟其位置有關（例：重力）
	* 重力是否為保守力？是的 \( \to \) potential energy（位能）
	* 電力是否為保守力？是的→電位能(electric potential energy)
	
* \( W = \overrightarrow{F} \cdot d \overrightarrow{s} \)
* 位能的變化 = 負的保守力作功
* 電位能的變化就是靜電力作功再乘以負號

### 電位能
* 一點電荷在電場中從初始位置 \( i \) 移動到最終位置 \( f \)，其電位能 \( U \) 的變化量 \( \Delta U \)
* \( \begin{align*}
\Delta U = U_f - U_i &= -W\\
&= - q \int^f_i \overrightarrow{E} \cdot d \overrightarrow{s} 
\end{align*}\)  
path integral (line integral)
* 其中 \( W \) 為外部電場的靜電力，將此點電荷由 \( i \) 移動到 \(f \) 所作的功
* \(\begin{case}
U = 0 通常位於 \( \infty \) 的地方 \\
U = -W_{\infty} 粒子由 \( \infty \) 靠近，靜電力所作的功
\end{case}\)
* 游離電子受地表的電場 \(overrightarrow{E} \) 作用，此電場  \(overrightarrow{E} \) 大小為 150 {^{N}}/_C 方向向下，所產生的靜電力-游離電子垂直向上移動了 \( d = 520 m \)，問此電子的電位能變化 \( \Delta U \)？

* \( \Delta U = -W \)
* \( \begin{align*} 
W = \overrightarrow{F} \cdot \overrightarrow{s} &= q	| \overrightarrow{E} | | \overrightarrow{s} | \cos(180\deg)\\
&= (-1.6 \times 10^{-19} C) \cdot 150 {^{N}}/_C \cdot 520m \cdot 9R?\\
&= 1.2 \times 10^{-14} j(joule) 
\end{align*} \)
* \( \Delta U = -W = -1.2 \times 10^{-14} j \)

## 電位<br>Electric Potential
* \( 
V \定義 \frac{U}{q_0}
\)
* 電位是一個純量（沒有方向性），SI 單位為 \( V \)(Voltage)
* \( 1 voltage = 1 {^{joule}}/_{coulumb} \\
1 福特 = 1 {^{焦耳}}/_{庫侖}\\
1 V = 1 {^{N \cdot m}}/_C\\
1 \frac{N}{C} = 1 \frac{V}{m}
\)