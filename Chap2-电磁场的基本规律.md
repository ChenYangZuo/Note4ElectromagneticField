# 2.1 电荷守恒定律

## 2.1.1 电荷及电荷密度

### 一、电荷体密度

$\Large \rho(r')=\lim\limits_{\Delta V' \to 0}{\Delta q \over \Delta V'}={dq \over dV'}$

### 二、电荷面密度

$\Large \rho_S(r')=\lim\limits_{\Delta S' \to 0}{\Delta q \over \Delta S'}={dq \over dS'}$

### 三、电荷线密度

$\Large \rho_l(r')=\lim\limits_{\Delta l' \to 0}{\Delta q \over \Delta l'}={dq \over dl'}$

### 四、点电荷

体积很小而电荷密度很大的带电小球的极限

## 2.1.2 电流及电流密度

$\Large i=\lim\limits_{\Delta t \to 0}{\Delta q \over \Delta t}={dq \over dt}$

### 一、体电流

$\Large \vec{J}=e_n\lim\limits_{\Delta S \to 0}{\Delta i \over \Delta S}=e_n{di \over dS}$

### 二、面电流

$\Large \vec{J}_S=e_n\lim\limits_{\Delta l \to 0}{\Delta i \over \Delta l}=e_n{di \over dl}$

### 三、线电流

## 2.1.3 电荷守恒定律与电流连续性方程

### 一、电荷守恒定律

电荷是守恒的，它既不能被创造，也不能被消灭，只能从物体的一部分转移到另一部分，或者从一个物体转移到另一个物体。

### 二、电流连续性方程

#### 1.积分形式

单位时间内从闭合面S内流出的电荷量等于闭合面S所限定的体积V中减少的电荷量

$\Large \oint_S\vec{J}\cdot d\vec{S}=-{dq \over dt}=-{d \over dt}\int_V\rho dV$

#### 2.微分形式

$\Large \oint_S\vec{J}\cdot d\vec{S}=-\int_V{\partial \rho \over \partial t} dV$

$\Large \oint_S\vec{J}\cdot d\vec{S}=\int_V\triangledown\cdot \vec{J}dV$

$\Large \int_V(\triangledown\cdot \vec{J}+{\partial \rho \over \partial t})dV=0$

$\Large \triangledown\cdot \vec{J}+{\partial \rho \over \partial t}=0$

#### 3.结论

恒定电流场是无散场



# 2.2 真空中静电场的基本规律

## 2.2.1 库仑定律 电场强度

$\displaystyle\Large \vec{F}={q \over 4\pi\varepsilon_0}\sum_{i=1}^N{q_i \over |r-r'_i|^3}(r-r'_i)$

$\displaystyle\Large \vec{E(r)}={1 \over 4\pi\varepsilon_0}\sum_{i=1}^N{q_i \over |r-r'_i|^3}(r-r'_i)$

## 2.2.2 静电场的散度与旋度

### 一、散度

#### 1.微分形式

$\Large \triangledown \cdot \vec{E}={\rho \over \varepsilon_0}$

空间任意一点电场强度的散度与该点处的电荷密度有关

电荷密度为正，称为发散源；电荷密度为负，称为汇聚源

#### 2.积分形式

$\Large \oint_S\vec{E}\cdot d\vec{S}={1 \over \varepsilon_0}\int_V \rho dV$

电场强度矢量穿过闭合曲面S的通量等于该闭合面所包围的总电荷与$\large \varepsilon_0$之比

### 二、旋度

#### 1.微分形式

$\Large \triangledown \times \vec{E}=0$

静电场是无旋场

#### 2.积分形式

$\Large \oint_C \vec{E}\cdot d\vec{l}=0$

单位正电荷沿静电场任一闭合路径移动一周，电场力不做功



# 2.3 真空中恒定磁场的基本规律

## 2.3.1 安培力定律 磁感应强度



## 2.3.2 恒定磁场的散度与旋度



# 2.4 媒质的电磁特性

## 2.4.1 电介质的极化电位移矢量

## 2.4.2 磁介质的磁化磁场强度

## 2.4.3 媒质的传导特性



# 2.5 电磁感应定律和位移电流

## 2.5.1 法拉第电磁感应定律

## 2.5.2 位移电流



# 2.6 麦克斯韦方程组

## 2.6.1 麦克斯韦方程组的积分形式

## 2.6.2 麦克斯韦方程组的微分形式

## 2.6.3 媒质的本构关系



# 2.7 电磁场的边界条件

## 2.7.1 边界条件的一般形式

## 2.7.2 两种特殊情况下的边界条件