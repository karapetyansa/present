
<br>

<br>

# Глава 2

## **Влияние рассеяния носителей на шероховатой поверхности на оптические свойства размерно-ограниченных систем**



### Межподзонное поглощение света

Схема оптических переходов
<br>
<div style="text-align: center;">
    <img src="./images/fig_2_1_1.jpg" width="40%">
</div>


<br>

`
\[
K(\Omega) = \frac{2 \pi e^2 }{V c n_0 \hbar \Omega m_e^2}\left( 1 - e^{-\beta_0 \hbar \Omega} \right) \int\limits_{-\infty }^{\infty} {dt \sum_{\alpha \alpha_1 \beta \beta_1} {\left\langle \alpha \left| (\hat{\boldsymbol{\mathbf{P}}} \boldsymbol{\mathbf{\xi}})  \right| \alpha_1 \right\rangle \left\langle \beta \left| (\hat{\boldsymbol{\mathbf{P}}} \boldsymbol{\mathbf{\xi}})  \right| \beta_1 \right\rangle}} \times\\
\times n_{\beta_1} \left(1-n_{\beta} \right)
{\left\lbrace  \left\langle \beta_1 \left| \exp \left(\frac{it\widetilde{H}}{\hbar}\right) \right|\alpha\right\rangle \left\langle \alpha_1 \left| \exp \left(-\frac{it\widetilde{H}}{\hbar}\right) \right|\beta\right\rangle \right\rbrace }_V
\]
`

<br>

`$n_\alpha = \left\{ \exp\left[ \beta \left( \varepsilon _\alpha - \xi \right) \right] + 1 \right\}^{- 1}$` — равновесная
функция распределения для электронов с энергией $\varepsilon{_\alpha}$

<br>

`
\[
\left\langle \alpha \left| \hat{P}^{(z)} \right| \beta \right\rangle = \frac{2}{a} i\hbar \delta_{k_\bot k'_\bot} \frac{n n_1}{n^2 - n_1^2} \left[(-1)^{n+n_1} -1 \right] , \; n \neq n_1,\\
\left\langle \alpha \left| \hat{P}^{(x)} \right| \beta \right\rangle = \hbar k_x \delta_{\alpha\beta}, \;
\left\langle \alpha \left| \hat{P}^{(y)} \right| \beta \right\rangle = \hbar k_y \delta_{\alpha\beta}.
\]
`


<br>

<br>

`
\[
\frac{1}{\tau_{\alpha\alpha_1}} = \frac{1}{\tau_0} \left(n^4 + n_1^4 \right)
\]
`

`
\[
\frac{1}{\tau_0}  = \frac{m_e}{2\hbar^3} \left(\frac{2\varepsilon_0}{a} \right)^2 \gamma_0
\]
`

`
\[
K(\Omega) = K_M \frac{1}{1+\left(\dfrac{\tau_0 }{17 \hbar} \Delta_0 \right)^2 }
\]
`

`
\[
K_M =\frac{2^{12} e^2 a^5 n_e }{\hbar cn_0 \pi^5 \gamma_0 3^3 \cdot 17}, \;
\Delta_0 =\hbar \Omega -3\varepsilon_0
\]
`



### Внутризонное поглощение света

<br>

`
\[
K(\Omega) = \frac{2 \pi e^2 n_e }{m_e c n_0 a \hbar \beta_0 \Omega^2} \int\limits_0^{\infty}x dx \int\limits_{-\infty}^{\infty}y dy \times \\
\times \exp{\left\lbrace  - 2\Gamma_0 |y| \left[ 1 - \frac{\delta_0}{\pi x |y|}\sin^2{\left( \frac{x|y|}{\delta_0}\right) } + \frac{1}{\pi} \mathrm{Si}{\left( \frac{2x|y|}{\delta_0}\right) } \right]  \right\rbrace   }
\]
`

`
\[
\delta_0 = 2\hbar \Omega \beta_0
\]
`

`
\[
\Gamma_0 = \pi^2 \left(\frac{\varepsilon_0}{\hbar \Omega} \right) \left( \frac{\gamma_0}{a^4} \right)
\]
`

`
\[
\mathrm{Si}(z) = -\frac{\pi}{2} + \int\limits_0^z{d\tau\frac{\sin{t}}{\tau}}
\]
`


### При низких температурах

<br>

`
\[
K(\Omega )=\frac{4\pi e^{2} n_{e} }{m_e c n_0 a \hbar\beta \Omega^2 } \frac{\Gamma_0 }{1+\Gamma_0^2 }
\]
`

<br>

#### В нижайшем приближении по взаимодействию электрона с шероховатой поверхностью $\Gamma_0 \ll 1$:

`
\[
K(\Omega )=\frac{2^4 e^2 n_e \gamma_0 m}{\pi c n_0 a\hbar^3 \beta_0 } \left(\frac{\varepsilon_0 }{\hbar\Omega } \right)^3
\]
`

#### При сильном взаимодействии $\Gamma _{0} \gg 1$:

`
\[
K(\Omega )=\frac{2^4 e^2 n_e a}{\pi^3 cn_0 \hbar } \frac{1}{\delta_0 } \left(\frac{a^4 }{\gamma_0 } \right)
\]
`



### Влияние лазерного излучения на оптические свойства квантовых пленок

<br>
`
\[
\hat{H}_c =\frac{1}{2m_c } \hat{P}^2 +\frac{e}{m_c c} (\hat{P}\xi )\sqrt{\frac{4\pi c^2 }{V} } (\hat{b}+\hat{b}^+ ) + \\ 
+\frac{e^{2} }{2m_e c^2 } \left(\frac{4\pi c^{2} }{V} \right)(\hat{b}+\hat{b}^+ )^2 +\hbar \omega \hat{b}^+ \hat{b}+eEz\equiv \hat{H}_c^0 +eEz
\]
`

#### Коэффициент межзонного поглощения электромагнитной волны

`
\[
K(\Omega )=\frac{4\pi e^2 }{V n_0 c\hbar \Omega } \left|\frac{p_{cv} \xi_0 }{m_0 } \right|^2 \times  \\
\times \sum _{\beta } \int\limits_{-\infty }^{\infty} dt \exp \left(i\Omega t-\frac{i e^2 E^2 t^3 }{6\hbar \mu } +\frac{ieEk_z t^2}{2\mu } \right)\times  \\ 
\times \left\{<\beta^c |\exp \left(\frac{it}{\hbar } \hat{H}_v^0 \right)\exp \left(-\frac{it}{\hbar } \hat{H}_c^0 \right)|\beta^c >\right\}_f  
\]
`


### Магнитоинфракрасный резонанс в объемном материале

<br>

`
\[
K(\Omega )=\frac{2e^2 }{n_0 c\hbar R^2 } \left|\frac{p_{cv} \xi_0 }{m_0 } \right|^2 \sqrt{\frac{2\mu }{\pi \hbar \omega } } \frac{1}{\gamma ^{\tfrac{1}{4} } } \times \\
\times \sum_n \int\limits_0^{\infty } \frac{d\tau }{\sqrt{\tau } } \cos \left(a\tau ^{3} -\Delta_n \tau +\frac{\pi }{4} \right)\exp \left(-\frac{\tau^2 }{2} \right)L_n (\tau^2 ) 
\]
`

где

` 
\[
\Delta_n =\frac{\hbar \Omega -E_g -\hbar \omega^* \left(n+{\frac{1}{2}} \right)}{\hbar \omega \sqrt{\gamma } } ; \; a=\frac{e^2 E^2 }{2 4\mu \omega^3 \hbar \gamma^{\frac{3}{2}} } ; \; \gamma =\frac{e^2 E_0^2 }{8 \mu \hbar \omega^3 }
\]
` 


Частотная зависимость первого пика магнетопоглощения в режиме магнитоинфракрасного резонанса. Кривые 1, 2, 3 получены соответственно для $a=0$; $a=0.4$; $a=0.8$

<br>
<div style="text-align: center;">
<img src="./images/fig_2_2_1.jpg" width="55%">
</div>


Частотная зависимость второго пика магнетопоглощения в режиме магнитоинфракрасного резонанса. Кривые 1, 2, 3 получены соответственно для $a=0$; $a=0.4$; $a=0.8$

<br>
<div style="text-align: center;">
<img src="./images/fig_2_2_2.jpg" width="55%">
</div>


### Размерно-инфракрасный резонанс в ПКЯ

<br>

<br>

` 
\[
K(\Omega )=K_0 \sum _{n} \, V_n^2 \times  \\
\times \left\{\frac{\pi }{2} +\int_0^{\infty } dt \exp \left(-\frac{x^2 }{2} \right)L_n \left(x^2 \right)\frac{\sin \left[x\left(\Delta_n -\delta x^2 \right)\right]}{x} \right\}
\]
` 

где

`  
\[
\Delta_n =\frac{\hbar \Omega -E_g -\hbar \omega^* \left(n+{\tfrac{1}{2}} \right)}{\hbar \sqrt{\gamma } } ; \; \omega^* =\omega_c +\omega_v
\] 
` 


Частотная зависимость межзонного поглощения света в режиме размерно-инфракрасного резонанса. Кривые 1, 2, 3 получены соответственно для $a=0$; $a=0.4$; $a=0.8$ 

<br>
<div style="text-align: center;">
<img src="./images/fig_2_2_3.jpg" width="55%">
</div>



### Оптические свойства квантовых проволок в присутствии резонансного лазерного излучения

<br>

<br>

`
\[
E_{\alpha }=\frac{\hbar^2 k^2_x}{2m^*_e}+\hbar \Omega_e\left(n+\frac{1}{2}\right)+\hbar {\omega }_e\left(m+\frac{1}{2}\right)
\]
`
<br>
`
\[
m^*_e=m_e{\left(\frac{\Omega_e}{\omega_e}\right)}^2,\;
\Omega_e={\left[{\omega }^2_e+{\omega_c}^2\right]}^{1/2},\;
\omega_c=\frac{eB}{m_ec\ }
\]
`


Схема энергетических зон полупроводниковой квантовой проволоки в поперечном магнитном поле и оптические переходы

<div style="text-align: center;">
<img src="./images/fig_2_3_1.jpg" width="32%">
</div>


Гамильтониан в представлении вторичного квантования для электронов в зоне проводимости в состоянии $\alpha $ в поле лазерного излучения поляризацией $\boldsymbol{\mathbf{\xi}}$

<br>
`
\[
\hat{H}=\sum_{\alpha } {\varepsilon_{\alpha } a^+_{\alpha } a_{\alpha }} + \hbar \omega_L b^+ b + {\left[\frac{2\pi \hbar e^2} {V \omega_L} \right]}^{\frac{1}{2}} {\sum_{\alpha \alpha_1}{\left|\frac{\boldsymbol{\mathbf{P}}_{\alpha \alpha_1} \boldsymbol{\mathbf{\xi}}}{m_e}\right|}}^2 a^+_{\alpha } a_{\alpha_1} (b^+ + b)
\]
`

<br>
Матричные элементы оператора импульса $\boldsymbol{\mathbf{P}}_{\alpha\alpha_1}$ на волновых функциях параболической квантовой проволоки в продольном магнитном поле

`
\[
{\left| P^X_{\alpha \beta }\right|}^2=\frac{\delta^2}{\sqrt{\left(1+\delta^2\right)}}{\left|P^Y_{\alpha \beta }\right|}^2, \;
\delta =\frac{\omega_c}{\omega_e},\\
\left| P^Y_{\alpha \beta }\right|^2=
\frac{m_e \sqrt{\left({1+\delta }^2\right)} \hbar\omega_e}{2} \left[  n \delta_{n,n_1+1} + (n+1) \delta_{n,n_1-1} \right]\delta_{k_x,k_x'}\delta_{m,m_1} , \\
{\left| P^Z_{\alpha \beta }\right|}^2=\frac{m_e \hbar\omega_e}{2} \left[ m \delta_{m,m_1+1} + (m+1){\delta }_{m,m_1-1} \right]  \delta_{k_x,k_x'} \delta_{n,n_1}
\]
`


### Коэффициент поглощения в поле ИК лазерного излучения Y-поляризации

<br>

`
\[
K\left(\Omega\right)=K_0{\sum_{nm}{\left|\left\langle \alpha_c | \alpha_v \right\rangle \right|}}^2 
\int\limits_{-\infty }^{\infty }dk_x \int\limits_{-\infty }^{\infty }{dt \exp{\left( -a t^2 -\frac{\Gamma_0 }{\left|k_x\right|}|t| \right) }} L_n\left(2at^2 \right)\times\\
\times {\exp \left\{\frac{it}{\hbar }\left[\hbar \Omega-E^*_g-\frac{\hbar^2 k^2_x}{2\mu^*}-m\left(\hbar\omega_e+\hbar\omega_v\right)-n\left(\hbar\Omega_e + \hbar\Omega_v \right)\right]\right\}\ }
\]
`

`
\[
K_0=\frac{\hbar \Omega e^2}{4\mu^* E_g^* n_0 c s}, \;
a=\frac{e^2 E^2}{8 m_e \hbar\Omega_e}, \\
\frac{1}{\mu^*}=\frac{1}{m^*_e}+\frac{1}{m^*_v},\;
m^*_v=m_v {\left(\frac{\Omega_v}{\omega_v}\right)}^2
\]
`


### Оптический переход I

<br>

<br>

`
\[
K\left(\Omega\right)=K_0\sum_{nm}{ {\lvert\langle \alpha_c | \alpha_v \rangle\rvert}^2 {\left[\frac{8\pi \mu^* \omega_f}{\hbar a}\right]}^{\frac{1}{2}} \mathrm{Re} \int\limits_0^\infty {dx e^{f^2\left(x\right)}\left[1-\Phi \left(f\left(x\right)\right)\right]}}
\]
`
<br>
`
\[
\Phi \left(z\right)=\frac{2}{\sqrt{\pi}}\int\limits_0^z {e^{-\tau^2}}d\tau , \\
f\left(x\right)={\left(\frac{\omega^2_f}{4a}\right)}^{\frac{1}{2}}\frac{1}{x}\left[1-ix\left(\frac{\Delta }{\hbar \omega_f}-x^2\right)\right],\;
\Delta =\hbar \Omega-E^*_g
\]
`


Зависимость первого пика межзонного поглощения света (в относительных единицах) от ${\Delta }/{\hbar {\omega }_f}$. Кривые 1, 2, 3 вычислены для $\xi =0.25,\; 0.05,\; 0.01$ соответсвенно

<br>
<div style="text-align: center;">
<img src="./images/fig_2_3_2.jpg" width="50%">
</div>


### Оптический переход II

<br>
`
\[
K\left(\Omega\right)=K_0{\left|\left\langle \widetilde{\alpha }_c |\widetilde{\alpha }_v\right\rangle \right|}^2 4{\left[\frac{2{\mu }^*{\omega }_f}{\hbar a}\right]}^{\frac{1}{2}}\times\\
\times Re\int\limits^{\infty }_0 {dx} f(x)\left\{-\sqrt{\pi }f\left(x\right)e^{f^2\left(x\right)}\left[1-\Phi \left(f\left(x\right)\right)\right]+1\right\}
\]
`

<br>
При $\xi <1$ форма линии поглощения определяется интенсивностью резонансного ИК излучения
`
\[
K\left(\Omega\right)=K_0{\left|\left\langle \widetilde{\alpha }_c |\widetilde{\alpha }_v\right\rangle \right|}^2 \pi z{\left[\frac{2^* \pi }{\hbar }{\left(\frac{8z}{a}\right)}^{1/2}\right]}^{1/2}e^{-z}\times\\
\times \left\{-\left[I_{3/4}\left(z\right)+\mathrm{sign}(\Delta) I_{-3/4}\left(z\right)\right]+\left(1+\frac{1}{4z}\right)\left[(I_{-1/4}\left(z\right)+ \mathrm{sign}(\Delta)  I_{1/4}\left(z\right)\right]\right\}
\]
`


Зависимость второго пика магнетопоглощения от ${\Delta }/{\hbar {\omega }_f}$ при различных значениях интенсивности резонансного $\left({\omega }_L=\Omega_e\right)$ лазерного излучения. Кривые 1, 2, 3 вычислены для $\xi =0.25,\ \ 0.05,\ \ 0.01$ соответсвенно.

<br>
<div style="text-align: center;">
<img src="./images/fig_2_3_3.jpg" width="50%">
</div>