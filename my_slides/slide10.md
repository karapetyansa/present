# Глава 1

## **Рассеяние носителей на шероховатой поверхности**



## Механизм рассеяния на шероховатой поверхности

<div id="left">
<br>

<br>

`
\[
V(x,y)=\frac{\partial E_{\alpha}}{\partial a}\Delta(x,y)\equiv V_{\alpha} \Delta(x,y)
\]
`
<br>
$\Delta(x,y)$ — случайная функция
</div>

<div id="right">
    <img src="./images/fig_1.png" width="50%">
</div>


### Для прямоугольной квантовой ямы с бесконечными стенками:

`
\[
E_n = \frac{\hbar^2 \pi^2 n^2}{2ma^2} \equiv E_0 n^2 \Rightarrow V_n = -\frac{2}{a}E_0 n^2
\]
`

------

### Для квантовой ямы с параболическим потенциалом:

`
\[
E_n=2\hbar \left[ \frac{2\Delta E_c} {m_e} \right]^\frac{1}{2} \frac{1}{a}\left( n + \frac{1}{2} \right) = \hbar \omega_e \left( n + \frac{1}{2} \right), V_n = -\frac{1}{a} \hbar \omega_e \left( n + \frac{1}{2} \right),
\]
`

`
\[
\hbar \omega_e = \frac{2\hbar}{a}\sqrt{\frac{2 \Delta E_c}{m_e}}
\]
`

$\Delta E_c$ — высота параболического потенциала на границе наноструктуры,

$\hbar \omega_e$ — энергия размерного квантования.



### Флуктуация поверхности в случае квантовой ямы

#### **Гауссова:** 
`
\[
\left\{ \Delta(x,y)\Delta(x',y') \right\}_V = \Delta^2 \exp \left\lbrace - \frac{1}{\Lambda^2} \left[ (x-x')^2 +(y-y')^2 \right] \right \rbrace \equiv F \left( \left| \boldsymbol{\rho} - \boldsymbol{\rho'} \right| \right),
\]
`
<br>
здесь: $\left| \boldsymbol{\rho} - \boldsymbol{\rho'} \right| = \sqrt{(x-x')^2 + (y-y')^2}$, $\Delta, \Lambda$ — высота и ширина гауссовой флуктуации соответственно, `$\left\{ ... \right\}_V$` описывает усреднение по реализации случайного процесса, $\Delta(x,y)$

#### **$\delta$-образная:**
`
\[
\label{eq:1_5}
\left\{ \Delta(x,y)\Delta(x',y') \right\} = \gamma_0\delta\left( \boldsymbol{\rho} - \boldsymbol{\rho'} \right) = \gamma\delta(x-x')(y-y')=\tilde{F} \left(\left| \boldsymbol{\rho} - \boldsymbol{\rho'} \right|\right)
\]
`

$\gamma_0$ определяет квадрат амплитуды флуктуации


### Флуктуация поверхности для одномерного электронного газа

#### **Гауссова:**
`
\[
\left\{\Delta(x)\Delta(x')\right\}=\Delta^2_0 \exp \left[-\frac{(x-x')^2}{\Lambda^2_0}\right] = F_0(x-x')
\]
`

#### **$\delta$-образная:**
`
\[
\left\{\Delta(x)\Delta(x')\right\}= \gamma_0\delta(x-x') = \tilde{F}_0(x-x')
\]
`



## Формула кубо

`
\[
\sigma _{ij} =\frac{\beta_0 e^2 }{2 V m^2 } \sum _{\alpha,\beta, \alpha_1,\beta_1} \hat{p}_{\alpha \beta }^{(i)} \hat{p}_{\alpha_1 \beta }^{(j)} \int\limits_{-\infty }^{\infty} {dt\left\langle a_{\alpha }^+ (t) a_{\beta }(t) a_{\alpha_1 }^+ a_{\beta_1 } \right\rangle}
\]
`

`
\[
K(\Omega) = \frac{2 \pi e^2}{V c n_0 \hbar \Omega m_e^2}\left( 1 - e^{-\beta_0 \hbar \Omega} \right) \sum_{\alpha \alpha_1 \beta \beta_1} {\left\langle \alpha \left| (\hat{\boldsymbol{\mathbf{P}}} \boldsymbol{\mathbf{\xi}})  \right| \alpha_1 \right\rangle \left\langle \beta \left| (\hat{\boldsymbol{\mathbf{P}}} \boldsymbol{\mathbf{\xi}})  \right| \beta_1 \right\rangle} \times\\
\times\int\limits_{-\infty }^{\infty} {dt e^{i\Omega t}\left\langle a_{\alpha }^+ (t) a_{\alpha_1 }(t) a_{\beta }^+ a_{\beta_1 } \right\rangle}
\]
`

здесь:
`
\[
a_{\alpha }^+ (t)= \exp\left(\frac{it\hat{H}}{\hbar } \right)a_{\alpha }^+ \exp\left(-\frac{it\hat{H}}{\hbar } \right), \;
\hat{H}=\sum _{\alpha }\varepsilon _{\alpha } a_{\alpha }^{+} a_{\alpha } +\sum _{\alpha ,\beta }{\left\langle \alpha  \right|} \hat{V}{\left| \beta  \right\rangle} a_{\alpha }^{+} a_{\beta }
\]
`



### Приближение времени релаксации

`
\[
\sigma_{ij}=\frac{\beta_0e^2}{Vm^2_e}\sum_{\alpha }{\left|{\hat{P}}^{(i)}_{\alpha \alpha }\right|}^2n_{\alpha }\left(1-n_{\alpha }\right)\tau_{\alpha \alpha }
\]
`

`
\[
K(\Omega) = \frac{4\pi e^2}{\hbar c V n_0 \Omega} \left| \frac{\boldsymbol{\mathbf{P_{\alpha\beta}}} \boldsymbol{\mathbf{\xi}}}{m_e^2} \right| \sum_{\alpha\beta}{\frac{\tau_{\alpha\beta}n_{\alpha}}{1+\frac{\tau^2_{\alpha\beta}}{\hbar^2}(\hbar\Omega+E_{\alpha}-E_{\beta})^2}}
\]
`

`
\[
\frac{1}{\tau_{\alpha\beta}}=\frac{\pi}{\hbar} \sum_{\gamma} {\left[ W_{\alpha\gamma} \delta \left(\varepsilon_{\alpha} - \varepsilon_{\gamma} \right) + W_{\beta\gamma} \delta \left(\varepsilon_{\beta} - \varepsilon_{\gamma} \right)\right]} 
\]
`

`
\[
W_{\alpha\beta}=\int{d\boldsymbol{\mathbf{r}} d\boldsymbol{\mathbf{r_1}} \Psi^*_\alpha(\boldsymbol{\mathbf{r}}) \Psi^*_\beta(\boldsymbol{\mathbf{r_1}}) V_\alpha V_\beta F \Psi_\alpha(\boldsymbol{\mathbf{r}}) \Psi_\beta(\boldsymbol{\mathbf{r_1}})}
\]
`



### Время релаксации для различных систем:
#### Квазидвумерные системы с бесконечным потенциалом и гауссовой флуктуации поверхности
`
\[
\frac{1}{\tau_a}=\frac{m_e}{\hbar^3}\pi{(\Delta \Lambda)}^2 V_n^2 \exp{\left[-\frac{1}{2}(\Lambda k_\bot )^2\right]} \mathrm{I}_0 \left[\frac{1}{2}(\Lambda k_\bot)^2\right]
\]
`

При низких температурах, когда $\Lambda k_\bot \ll 1$:
`
\[
\frac{1}{\tau_a}=\frac{m_e }{\hbar^3}\pi (\Delta \Lambda)^2 V_n^2
\]
`

#### Для случая $\delta$-образной флуктуации поверхности
`
\[
\frac{1}{\tau_a}=\frac{m_e}{\hbar^3}\gamma_0 V_n^2
\]
`


#### Одномерные квантовые системы с гауссовой флуктуацией поверхности
`
\[
\frac{1}{\tau_\alpha}=\frac{2 m_e}{\hbar^3} \frac{V_n^2}{\left|k_x\right|} \frac{\Delta^2_0\Lambda_0\sqrt{\pi}}{2} \left(1+\exp\left[-\Lambda^2_0 k^2_x \right] \right)
\]
`

#### Одномерные квантовые системы с $\delta$-образной флуктуации поверхности
`
\[
\frac{1}{\tau_\alpha}=\frac{2 m_e}{\hbar^3} \frac{V_n^2}{\left|k_x\right|}\gamma_0
\]
`



### Влияние поперечного электрического поля на процессы рассеяния

<div id="left23">
`
\[
U(z)=\frac{m_e \omega^2 }{2} z^2 +eEz
\]
`
<br>
`
\[
\hbar \omega =\frac{2\hbar }{a} \sqrt{\frac{2\Delta E_c }{m_e} }
\]
`
<br>
`
\[
E_{n,k_{\bot } } =\frac{\hbar^2 k_{\bot }^2 }{2m_e} + \hbar \omega \left(n+\frac{1}{2} \right)-\Delta_c
\]
`
<br>
`
\[
k_{\bot }^2 =k_x^2 +k_y^2, \;
\Delta_c =\frac{e^2 E^2 }{2m_e \omega^2}
\]
`
<br>
</div>
<div id="right13">
    <img src="./images/fig_1_2_1.jpg" width="80%">
</div>

`
\[
\Psi^{(c)}_{k_x,n,m}(x,y,z)=\frac{e^{ik_x x}}{\sqrt{L_x}}\frac{e^{ik_y y}}{\sqrt{L_y}}{\left(\frac{\lambda }{\pi}\right)}^{\frac{1}{4}} 
\frac{1}{\sqrt{2^nn!}}H_n\left[(z-z_0)\sqrt{\lambda }\right]e^{-\frac{\lambda }{2}(z-z_0)^2}
\]
`


### Взаимодействие с шероховатой поверхностью
`
\[
W_{n} =\frac{\partial E_n }{\partial a} \Delta(x,y) \equiv -\frac{1}{a} \left[ E_n +2\Delta_c \right] \Delta (x,y)=V_n \Delta (x,y)
\]
`

<br>

`
\[
\frac{1}{\tau _{\alpha } } =\frac{\gamma_0 m_e (\hbar\omega)^2 }{\hbar^3 a^2 } \left[\left(n+\frac{1}{2} \right)+N_c \right]^2, \;
N_c =\frac{2\Delta_c }{\hbar \omega } 
\]
`