# 2017/9/29 上課筆記
## 課前
* 向量內積外積的運算方式很重要，甚至會影響能不能過這門課
* 有遇什麼問題請盡早跟助教、老師反映出來
* temp previous
	* 量
		* length
		* mass
		* time
		* electric current
		* temperature
		* amount of substance(mol)
		* luminous intensity(cd)
	* prefix
		* \( 10^{15} \): penta

## 科學符號
* 例如 \( 1.5 \times 10^3 \)
* 答案請都使用工程計算機算出，並科學符號代表
* 不能用 
	* \( \sqrt{3} \)
	* \( \frac{1}{3} \)

## 有效數字<br>Significant Figures
### 數字相乘或相除時
答案的有效數字的位數要和最少的有效數字位數相同

#### 範例：\((16.3cm)(4.5cm) \)
計算機得出 \( 73.35{cm}^2 \)，但因為乘數最少有效數字為 2 故實際上計算結果之有效數字亦為 2，故解答應為 **73**\( cm^2 \)

### 當數字相加或相減時
數量相加或相減時，**結果的小數位數要和任何一數中小數位數最少的相同**

#### 範例： \( 168 + 3.45 \)
計算結果為 171.45，但是因為有效位數為 3（168）故解答應為 171

#### 範例： \( 1.001 + 0.003 \)
計算結果為 1.004，正解也應為 1.004（小數位數最少者之小數位數為 3）

### 科學記號來代表有效數字
* 有效數字為 2
	* \( 1.5 \times 10^3 \)
	* \( 1.5 \times 10^{-3} \)
* 有效數字為 3
	* \( 1.50 \times 10^{-3} \)

### 三角函數
（略）

## 向量和純量<br>Vectors and Scalars
### 純量<br>Scalars
* 有數目有單位，但沒有方向

### 向量<br>Vectors
* **兩點**或**一點、一方向**決定向量
* 解題方式
	* 圖解法
	* 公式
* \( \overrightarrow{A} = \overrightarrow{B} \)  
  (missed)

* \(  | \overrightarrow{a} |  = \sqrt{a_x^2 + a_y^2 + a_z^2} \)

### 位移與...<br>Displacement
![照片](IMG_20170920_100117.jpg)

### 向量加法求法

#### 圖解法
* 將一向量平移使其成三角形，其不相交之兩點的向量即為和向量

### 內積<br>Inner Product<br>Dot Product
\( \begin{align*}
\overrightarrow{A} \cdot \overrightarrow{B} &= | \overrightarrow{A} | | \overrightarrow{B} | \cos{\theta} \\
&= ( a_x \hat{i} + a_y \hat{j} + a_z \hat{k} ) \cdot (b_x \hat{i} + b_y \hat{j} + b_z \hat{k} \\
&= a_xb_x + a_yb_y + a+zb_z 
\end{align*} \)

### 外積<br>Outer product<br>Cross product
$$ \overrightarrow{A} \times \overrightarrow{B} = \overrightarrow{C} $$

* 法向量的方向判定方式：安培右手定則
	1. 將兩個向量起端擺在同一原點上
	1. 將四指從第一向量彎向第二向量的方向
	1. 拇指指的方向即為法向量方向

#### 外積的求解方式
\( \overrightarrow{\mu} = ( \mu_1, \mu_2, \mu_3 )\\
\overrightarrow{v} = (v_1, v_2, v_3) \)

\(\overrightarrow{\mu} \times \overrightarrow{V} = \)

![照片](IMG_20170920_101308.jpg)

### 例題：\( \overrightarrow{A} = (1, 2, 2) = 1 \hat{i} + 2\hat{j} + 2\hat{k} \\ \overrightarrow{B} = (-5, 7, -9) = 5 \hat{i} + 7 \hat{j} + (-9) \hat{k} \)
\( \overrightarrow{A} + \overrightarrow{B} = -4 \hat{i} + 9 \hat{j} - 7 \hat{k} \\
\overrightarrow{A} - \overrightarrow{B} - 6\hat{i} -5 \hat{j} + 11 \hat{k} \\
3\overrightarrow{A} = 3\hat{i} + 6\hat{j} + 6\hat{k} \\
單位向量 = \\
\overrightarrow{A} \cdot \overrightarrow{B} = 1 \times\\
\overrightarrow{A} \times \overrightarrow{B} = \)

![照片](IMG_20170920_103737.jpg)
單位向量 = \\

### 向量分量
* 向量 \( \overrightarrow{A} \) 在 x-y 平面上與夾角 \( \theta \)
* \( 
A_x = A\cos{\theta} \\
A_y = A\sin{\theta} \\
( A_x \vertical_to A_y )
\)

![照片](IMG_20170920_104628.jpg)

## 三大運動：平移、轉動、振動<br>Translation, Rotation and Vibration

