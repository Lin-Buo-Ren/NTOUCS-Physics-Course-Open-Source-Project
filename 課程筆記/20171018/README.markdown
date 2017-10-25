# 普通物理 20171018 筆記
## 高斯定律<br>Guass's Law
* 在**封閉的高斯曲面**上每個點的電場與**該曲面所圍繞的淨電荷**產生關聯

### 高斯曲面
* 人想像出來的一個曲面

### 通量<br>Flux
瞄準一截面積為 \( A \) 之正方形環，氣體之速度均勻速度 \( \overrightarrow{V} \)

\( \Phi \) 表示氣體通過此環的體積流率（單位時間內通過該截面之體積）即為通量

流率隨速度 \( \overrightarrow{V} \) 與環平面的夾角而變

if \( \overrightarrow{V} \normal \) 於此面，流率 \( \Phi = VA \)

\( \Phi = VA \cos \theta = \overrightarrow{V} \cdot \overrightarrow{A} \)

* \( \overrightarrow{A}：面積向量 \)

### 電場通量
\( \overrightarrow{ \Phi } = \sum \overrightarrow{E} (missing 1032) \)

\(
\Phi = \oint \overrightarrow{E} \cdot d \overrightarrow{A}
\)

* 通過一封閉高斯曲面的電場通量
* \( \oint  \) 代表積分是在封閉的曲面（非開放表面）上進行
* SI 單位： \frac{N}{C} \cdot m^2
* \( \Phi \正比 E \正比 通過每單位面積的電場線數目 \)

#### 例題：一不均勻電場 \( \overrightarrow{E} = x \hat{i} + 4.0 \hat{j} \) 於一個高斯立體面（E：\( {^N}/_C \)、\( x \) 單位：\( m \) ），試問通過右面、左面、及頂面的電通量？
* ![graph1044]()
* \( \begin{align*}
\Phi_右 &= \int \overrightarrow{E} \cdot d \overrightarrow{A}\\
&= \int (3.0 \times \hat{i} + 4.0 \hat{j}) \cdot (dA \hat{i})\\
&= \int(3.0)(dA) \hat{i} \cdot \hat{i} (4.0)(dA) \hat{i} \cdot \hat{i}\\
&= \int3.0 \times dA\\
&= 3.0 \int x dA\\
&= (3.0)(3.0) \int dA \\
&= 9 {^N}/_C \cdot 4.0 m^2\\
&= 3.6 {^{N \cdot m^2}}/_C\\
\Phi_左 &= -12 {^{N \cdot m^2}}/_C\\
\Phi_上 &= \int (3.0 \times \hat{i} + 4.0 \hat{j}) \cdot (dA\hat{j}) \\
&= 16 {^{N \cdot m^2}}/_C
\end{align*} \)

* 高斯定律描述電場通過封閉曲面（高斯面）之總通量 \( \Phi \) 與該區面內之淨電量 \( q_{enc} \) 之間關係
* \( \epsilon_0 \Phi = q_{enc} \)
* 通量定義帶入：\( \epsilon_0 \oint \overrightarrow{E} \cdot d \overrightarrow{A} = q_{enc} \)
* 如果 \( q_{enc} \)為正，淨通量向外  
如果 \( q_{enc} \)為負，淨通量向內

### 例題 - 5 個帶電的塑膠體與一個不帶電的銅幣，圖中顯示了一個高斯面 \( S \) 的截面
![graph 1114]()
* 如果 \( q_1 = q_4 = 3.1nC\)、\(q_2 = q_5 = -5.9 nC \)、 \( q_3 = 3.1nC \)，則此高斯面的通量為若干？
* \( \frac{q_enc}{\epsilon_0} = \frac{q_1+q_2+q_3}{\epsilon_0} = \frac{3.1 \times 10^{-9}C + (-5.9) \times 10^{-9}C - 3.1 \times 10^{-9}C}{8.85 \times 10^{-12} {^{C^}}/_{N^2 \cdot m^2}} = -670 {^{N \cdot m^2}}/_C
\)

### 高斯定律 \( \to \) 庫侖定律
* 高斯定律和庫侖定律是描述靜電 \( F \) 電荷與電場之間關係的不同方式
* 一個正的點電荷 \( q \) 在其周圍為中心畫出一半徑為 \( r \) 的同心球形高斯面
* ![graph 1116]()
* 球體積公式： \frac{4}{3}
* \(
\epsilon_0 \oint \overrightarrow{E} d \overrightarrow{A} = \epsilon_0 \oint E \cdot dA\\
\epsilon_0 E \oint dA = q_{enc}\\
\epsilon_0 E ( 4 \pi r^2) = q_{enc}\\
E = \frac{1}{4 \pi \epsilon_0} \frac{q_{enc}}{r^2}\\
F = q_0 E = \frac{1}{4 \pi \epsilon_0}\frac{q_{enc}q_0}{
r^2}
(missing?)
\)
* 帶電的孤立導體額外電荷置於一孤立導體，這些電荷將全部移動之導體表面，在導體內部將無任何電荷（例：雷打中飛機）
* 均勻帶電球殼對球殼外的點電荷有吸引力或排斥力就好像所有的電荷均集中於球心上
#### 一半徑為 \( R \)、總電量 \( q \) 之球殼
* ![graph 1139]()
* case 1  
\(
	r \ge R\\
	E = \frac{1}{4 \pi \epsilon_0}\frac{q}{r^2}
	r < R \to E = 0（球殼內無電場）	
\)
* case 2：黑點代表半徑為 \( R \) 之球形對電荷分佈，其體電荷密度 \( \rho \)。同心球形 \( r \lt R \) 之高斯面
* ![graph 1139]()
