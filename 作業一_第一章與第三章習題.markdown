{% extends "Page design/Inner page.template.markdown" %}
{% block page_content %}
# 作業一 - 第一章與第三章習題<br />HW#1-CH1 & CH3
## 第 01 章，第 001 問題<br />Chapter 01, Problem 001
地球是一個半徑約為 $$6.37 × 10^6 公尺$$ 的球體。它的 **(a)** 球周長、**(b)** 表面積以及 **(c)** 它的體積為何？  
Earth is approximately a sphere of radius $6.37 × 10^6$ m. What are **(a)** its circumference, **(b)** its surface area, and **(c)** its volume?

### (a) 球周長
#### 解決方案<br />Solution
代入球周長公式：  
$$
球周長 = 2 \times 半徑 \times \pi = 2 \times (6.37 \times 10^6公尺) \times \pi
 = 2 \times (6.37 \times 10^3公里) \times \pi \approx 40023.89041 公里
$$

#### 答案<br />Answer
約 40023.89041 公里

### (b) 表面積
#### 解決方案<br />Solution
代入球表面積公式：  
$$
球表面積 = 4\pi 半徑 ^2 = 4\pi(6.37 × 10^3 公里)^2 \approx 509904363.8 平方公里(km^2)
$$

#### 答案<br />Answer
約 509904363.8 平方公里

### (c) 體積
#### 解決方案<br />Solution
代入球體積公式：
$$
球體積 = \frac{4\pi 半徑^3}{3} = \frac{4\pi (6.37 \times 10^3 公里)^3}{3} \approx 1.0827 \times 10^{12} 立方公里(km^3)
$$

#### 答案<br />Answer
約 $$1.0827 \times 10^{12}$$ 平方公里

## 第 01 章，第 024 問題<br />Chapter 01, Problem 024
California 海灘良好的細沙粒為有 $$50 \mu m$$ 平均半徑且成份為密度為 $$2.6 × 10^3 kg/m^3$$ 的二氧化矽的類球體。多少質量的細沙粒的總表面積（所有單一球體的表面積和）會相等於邊長 1.2 公尺的立方體的表面積？  
Grains of fine California beach sand are approximately spheres with an average radius of $$50 \mu m$$ and are made of silicon dioxide, which has a density of $$2.6 × 10^3 kg/m^3$$. What mass of sand grains would have a total surface area (the total area of all the individual spheres) equal to the surface area of a cube 1.2 m on an edge?

### 解決方案<br />Solution

1. 代入球表面積公式：  
$$單一細沙粒表面積 = 4\pi(半徑)^2 = 4\pi (50微米) ^2 = 4\pi (50 \times 10^{-6} 公尺) ^2 \approx 3.14 \times 10^{-8}平方公尺$$
1. 代入立方體表面積公式：  
$$立方體表面積 = 6 \times 邊長^2 = 6 \times (1.2公尺)^2 = 8.64平方公尺$$
1. $$表面積相等之細沙粒數量 = \frac{立方體表面積}{單一細沙粒表面積} = \frac{8.64平方公尺}{3.14 \times 10^{-8}平方公尺} \approx 275159235 $$
1. 代入球體積公式：
$$
一粒細沙粒體積 = \frac{4\pi 半徑^3}{3} = \frac{4\pi (50 \times 10^{-6} 公尺)^3}{3} \approx 5.24 \times 10^{-13}立方公尺
$$
1. 代入密度公式
$$
一粒細沙粒的質量 = 一粒細沙粒體積 \times 二氧化矽密度 = 5.24 \times 10^{-13}立方公尺 \times (2.6 \times 10^3 公斤/立方公尺) = 1.36 \times 10^{-9} 公斤
$$

1. $$表面積相等之細沙粒質量 = 表面積相等之細沙粒數量 \times 一粒細沙粒的質量  = 275159235 \times (1.36 \times 10^{-9}) 公斤 \approx 0.374 公斤 $$

## Chapter 01, Problem 029
On a spending spree in Malaysia, you buy an ox with a weight of 28.5 piculs in the local unit of weights: 1 picul = 100 gins, 1 gin = 16 tahils, 1 tahil = 10 chees, and 1 chee = 10 hoons. The weight of 1 hoon corresponds to a mass of 0.3779 g. When you arrange to ship the ox home to your astonished family, how much mass must you declare on the shipping manifest?

## 參考資料<br />Reference data
* [小学数学计算题中的计数单位必须加括号吗_百度知道](http://zhidao.baidu.com/question/437142105.html)
* [Sphere Circumference, Surface Area and Volume](http://www.neoprogrammics.com/spheres/circumference_area_volume.php)
{% endblock %}