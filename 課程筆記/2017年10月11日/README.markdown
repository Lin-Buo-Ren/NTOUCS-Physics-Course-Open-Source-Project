# 2017年10月11日筆記
## Charging by Induction<br>誘導帶電
* 怎麼讓一個電中性的物質帶電？透過誘導帶電(Charging by Induction)

![graph0950](graph0950a.jpg)

![graph0950](graph0950b.jpg)

![graph0950](graph0950c.jpg)

![graph0950](graph0950d.jpg)

![graph0950](graph0950e.jpg)

* 原子由帶正電的質子(proton)、帶負電的電子(electron)與電中性的中子(neutron)
* 質子與中子彼此緊密被束縛在一起
* 測不準定律：不能預測電子會在哪裡出現

## 庫侖定律<br>Coulomb's Law
![graph](graph0957.jpg)
![graph](coulumb-law-contract-force.jpg)

* \(
\overrightarrow{F} = K_e \frac{q_1 q_2}{r^2} \hat{r}\\
k_e：庫侖常數(coulomb's constant)，8.99\times 10^9 {^{N \cdot m^2}}/_{c^2} = \frac{1}{4 \pi \epsilon_0} （\epsilon_0(permittability?) = 8.85 \times 10^{-12} {^{C^2}}/_{N \cdot m^2}\\
\hat{r}：代表兩粒子延伸軸的單位向量\\
r：兩粒子的距離
\)

### 與牛頓定律相比較
* \(
\overrightarrow{F} = G \frac{m_1 m_2}{r^2} \hat{r}\\
G：重力常數
\)
* 兩者差異：牛頓定律只有相吸力，但是庫侖定律有排斥力
* 兩者皆遵守疊加定律（後述）

## 公制(SI)單位
* \( 
1C = (1A) (1s) 
\)

## 疊加定律（嚴重 miss）
* 以粒子為例：  
\(
\overrightarrow{F_{1, net}} = \overrightarrow{F_{1, 2}} + \overrightarrow{F_{1, 2}} + \cdots + \overrightarrow{F_{1, n}}
\)
* ![view1026]()
* 兩正電粒子固定在 \( x \) 軸，其電量(missed)
* \(
F_{13} = \frac{1}{4\pi \epsilon_0} \frac{|q_1| |q_2|}{}	
\)

## 物理量的量子化
* 電流是由許多基本電荷所構成的不連續
* (missed)
* ![photo 1041]()
* 電子和質子電量大小皆為 \( e \)
* | 粒子 | 符號 | 大小 |

### 例題：相距 \( 4.0 \times 10^{-15} m \) 的兩個質子間靜電排斥例的大小為何？
\( \begin{align*}
F &= \frac{1}{4\pi \epsilon_0} \frac{e^2}{r^2}\\
&= 8.99 \times 10^9 {^{N \cdot m^2}} / _{c^2} \times \frac{1.602(missed)}{}\\
&= 14N
\end{align*} \)

\( \begin{align*}
m_p = 1.67 \times 10^{-27} kg\\
F &= G\frac{m_p m_p}{r^2} = 6.67 \times 10^{-11} {^{N \cdot m^2}}/_{kg^2} \frac{(1.67 \times 10^{-27} kg)^2}{(4.0 \times 10^{-15} m)^2}\\
&= (missed)
\end{align*} \)

## 電場<br>Electric Field
* 電場是向量
* 每個電荷都會在其周圍產生一個電場
* \(
\overrightarrow{E} = \frac{\overrightarrow{F}}{q_0}\\
q_0：測試電荷
\)
* 如何定義帶電物附近各點的電場？首先，在點 \(p\) 上放置一正電荷 \( q_0 \)（測試電荷），測量其所受的靜電力 \( \overrightarrow{F} \)，\( p \) 點處由帶電物所造成的電場 \( \overrightarrow{E} = \frac{\overrightarrow{F}}{q_0} \)

## 電場線
* 想像出來的概念
* 電場線與電場向量間的關係
	1. 在任一點電場線切線方向為該點電場方向
	1. 與電場線垂直的單位面積中所包含的電場線的數目 \( 正比 \) 該處電場的大小
* ![photo1042](graph1042.jpg)
* 電場線由正電荷

## 由點電荷產生的電場
* \(
\overrightarrow{F} = \frac{1}{4 \pi \epsilon_0} \frac{q_1 q_2}{r^2} \hat{r}\\
\overrightarrow{E} = \frac{\overrightarrow{F}}{q_2}
\)
* 淨靜電力(missed1116)

### 例題：三個距離原點皆為 \( d \) 的粒子，其帶電量分別為 \( q_1 = +2Q \)、\( q_2 = -2Q \)、\( q_3 = -4Q \)，則原點處的淨電場為？
![graph1116](graph1116.jpg)

\( 
E_1 = \frac{1}{4\pi\epsilon_0} \frac{2Q}{d^2} \\
\begin{cases}
E_1 \sin \theta\\
E_1 \cos \theta
\end{cases}
E_2 = \frac{1}{4\pi\epsilon_0} \frac{2Q}{d^2} \\
\begin{cases}
E_2 = \sin\theta\\
E_2 = \cos \theta
\end{cases}
E_3 = \frac{1}{4\pi\epsilon_0} \frac{4Q}{d^2}
\begin{cases} 
E_3 = \sin\theta
E_3 = \cos\theta
\end{cases}
\)

## 電荷的一些量測值
| 分類 | 符號 | SI單位 |
|:---:|:----:|:-----: |
| 電荷 | \( q \) | C
| 線電荷密度<br>Linear Charge Density | \(\lambda\) | \({^C}/_{m^2}\) |
| 面電荷密度<br>? Charge Density | \( \sigma \) | \( {^C}/{_{m^3}} \) |
| 體電荷密度<br>? Charge Density | \(\rho\) | \({^C}/_{m^3}\) |

### 補充：常見的希臘文字
| 希臘文字 | 英文名稱 |
| :--: | :--: |
| \( \alpha \) | alpha |
| \( \beta \) | beta |
| \( \gamma \) | gamma |
| \( \delta \) | delta | 
| \( \epsilon \) | epsilon | 
| \( \zeta \) | zeta |
| \( \kappa \) | kappa |
| \( \lambda \) | lambda |
| \( \rho \) | rho |
| \( \sigma \) | sigma |
| \( \phi \) | phi | 
| \( \psi \) | psi |
| \( \omega \) | omega |


### 例題：半徑 \( R \)且帶正均勻線電荷密度 \( \lambda \) 的細圓環，則 \( p \) 點（在圓環的中心軸上與圓環平面相距 \( Z \)）處的電場 \( \overrightarrow{E} \) 為何？
* ![graph](graph1135.jpg)
* 在水平面上的電場完全互相抵銷掉
* \(\begin{align*}
dq = \lambda ds \\
dE &= \frac{1}{4 \pi \epsilon_0} \frac{dq}{r^2}\\
&= \frac{1}{4 \pi \epsilon_0} \frac{\lambda ds}{r^2}\\
&= \frac{1}{4 \pi \epsilon_0} \frac{\lambda ds}{(Z^2 + R^2)}
\end{align*}\)
* \(
\cos \theta = \frac{Z}{r} = \frac{Z}{Z^2+R^2}^{\frac{1}{2}}\\
dE\cos\theta = \frac{1}{4 \pi \epsilon_0}  \frac{Z}{(Z^2 + R^2)^\frac{1}{2}} \frac{\lambda ds}{(Z^2 + R^2)^\frac{1}{2}}
= \frac{1}{4 \pi \epsilon_0} \frac{Z \lambda ds}{(Z^2 + R^2)^\frac{1}{2}}
\)

* \(
E = \int dE\cos \theta = \int^{2\pi R}{0}ds \frac{\lambda}{4\pi \epsilon_0} \frac{Z}{(Z^2 + R^2)^\frac{1}{2}}
\)
* ![board]()
