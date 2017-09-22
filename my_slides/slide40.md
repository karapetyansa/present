# Глава 4

## **Явления переноса в наноструктурах в поперечном электрическом поле с учетом рассеяния на шероховатой поверхности**



### Подвижность в поперечном электрическом поле

`
\[
\sigma_{xx} =\frac{e^2 }{a\pi \hbar^2 \beta_0 } \sum_n\tau_n \ln \left(1+e^{-\beta \xi_n } \right)
\]
`

Подвижность невырожденного газа
`
\[
\mu_{xx} =\mu_{xx}(0)\frac{1}{\left(1+2 N_c \right)^2 }
\]
`
где
`
\[
\mu _{xx} (0)=\frac{e}{m} \left(\frac{\hbar a^4 }{2\gamma_0 \Delta E_c } \right)
\]
`


### Учет двух механизмов рассеяния

`
\[
\frac{1}{\tau_n } =\frac{1}{\tau_0 } +\frac{1}{\tau_f }
\]
`

`
\[
\frac{1}{\tau _{f} } =\left(\frac{m\omega }{2\pi \hbar } \right)^{\frac{1}{2} } \frac{E_1^2 m k_B T}{\hbar^3 v^2 \rho }
\]
`
<br>
`
\[
\mu_{xx} =\mu _{xx}(0)\frac{1}{\left(1+2N_c \right)^2 +\Delta }
\]
`

`
\[
\Delta =\left(\frac{m\omega }{2\pi \hbar } \right)^{\frac{1}{2} } \left(\frac{E_1 }{\hbar \omega } \right)^2 \frac{4k_B T a^2 }{\rho v^2 \gamma }
\]
`



### Влияние поперечного электрического поля на подвижность в нанопроволоках

`
\[
E_{\alpha }^c =\frac{\hbar^2 k_x^2}{2m_e} +E_{nm}^c, \\
E_{\alpha }^v =\Delta_0 -\frac{\hbar^2 k_x^2 }{2m_v } +E_{nm}^v
\]
`
здесь
`
\[
E_{nm}^c =\hbar \omega_e \left(n+k+1\right)-\Delta_c , \\
E_{nm}^v =\hbar \omega_v \left(n+k+1\right)-\Delta_v ,
\]
`

`
\[
\Delta_c =\frac{e^2 E^2 }{2m_e \omega_у^2}, \; \Delta_v =\frac{e^2 E^2 }{2m_v \omega_v^2 }
\]
`


Схема зонной структуры, рассматриваемой низкоразмерной структуры. Сплошными линиями показаны две нижайшие размерно-квантованные зоны ($c$ — зоны проводимости, $v$ — валентные зоны) , пунктирными линиями изображены две нижайшие размерно-квантованные зоны в поперечном электрическом поле; $\xi $ — химический потенциал
<img src="./images/fig_4_4_1.jpg" width="50%">



### Подвижности для электронов и дырок

`
\[
\mu =\frac{\mu_0\sqrt{\pi } }{2\sum_{nm} F(\eta_{nm}^c )} \sum_{nm}\left\{\frac{\ln \left[\exp \left(\eta _{nm}^c \right)+1\right]}{\left(n+m+1+N_c \right)^2 } +\left(\frac{\Delta E_c }{\Delta E_v } \right)\frac{1}{p} \frac{\ln \left[\exp \left(\eta_{nm}^v \right)+1\right]}{\left(n+m+1+N_v \right)^2 } \right\}
\]
`

Здесь введены обозначения:
`
\[
\mu_0 =\frac{4R^4 e}{\gamma \Delta E_c } \sqrt{\frac{k_0 T}{2\pi m_c } }, \;
R=\frac{a}{2}, \;
N_c =\frac{2\Delta_c }{\hbar \omega_c }, \;
N_v =\frac{2\Delta_v }{\hbar \omega_v },\\
\eta_{nm}^c =\frac{1}{k_0 T} \left[\xi -\hbar \omega_c \left(n+m+1\right)+\Delta_c \right],\\
\eta_{nm}^v =\frac{1}{k_0 T} \left[-\xi -\hbar \omega_v \left(n+m+1\right)+\Delta_0 +\Delta_v \right],\\
F(\eta_{nm}^c )=\int\limits_0^{\infty }{\frac{dx}{\exp \left(x^2 -\eta_{nm}^c \right)+1}}  ,
\]
`


Условие электронейтральности
`
\[
p\sqrt{\frac{m_c }{m_v } } \sum_{n,m}\int\limits_{0}^{\infty }{\frac{dx}{\exp \left(x^2 -\eta_{nm}^c \right)+1}}  =
\sum_{n,m}\int\limits_0^{\infty}{\frac{dx}{\exp \left(x^2 -\eta_{nm}^v \right)+1}}
\]
`


### Частные случаи

#### Невырожденный электронный газ

`
\[
\mu =\frac{\mu_0}{\left(1+N_c \right)^2 }
\]
`

#### Вырожденный электронный газ

`
\[
\mu = \frac{\sqrt{\mu_0 2\pi}}{4\left(1+N_c \right)^2 } \left[\frac{1}{k_0 T} \left(\Delta_0 +\Delta_c +\Delta_v -\hbar \omega_v -\hbar \omega_c \right)\right]^{\frac{1}{2} }
\]
`


Зависимость подвижности (в относительных единицах) от напряженности поперечного электрического поля. $R=330 Å$

<img src="./images/fig_4_2_2.jpg" width="50%">


Зависимость подвижности (в относительных единицах) от напряженности поперечного электрического поля. $R=990 Å$

<img src="./images/fig_4_2_3.jpg" width="50%">



### Особенности подвижности в нанопроволоках в поперечных электрическом и магнитном полях

`
\[
\hat{P}^{(x)}_{\alpha \beta }=\hbar k_x{\left(\frac{\omega_y}{\Omega_y}\right)}^2 \delta_{\alpha \beta }
\]
`
<br>
`
\[
\sigma_{xx}=\frac{2 e^2\hbar}{\beta_0 \pi^2 m^*_x \gamma_0} \sum_{nm}{\frac{\ln \left[1+\exp\left(\beta_0 \xi_{nm}\right)\right]}{\left[\hbar \omega_y \frac{\omega_y}{\Omega_y}\left(n+\frac{1}{2}\right)+\hbar \omega_z\left(m+\frac{1}{2}\right)+2\Delta_c\right]^2}} 
\]
`
<br>
`
\[
\xi_{nm}=\xi -\hbar \Omega_y \left(n+\frac{1}{2}\right)-\hbar \omega_z\left(m+\frac{1}{2}\right)+\Delta_c,\;
\beta =\frac{1}{k_0 T}
\]
`


#### Подвижность носителей (электронов и дырок) в нанопроволоке:
<br>
`
\[
\mu =\frac{eR^2{\hbar }^2}{m^*_x \gamma_0}\frac{1}{\sqrt{2m^*_x \beta_0}\sum_{nm}{F\left(\xi_{nm}\right)}}\sum_{nm}{\frac{\ln \left[1+{\exp \left(\beta {\xi }_{nm}\right)\ }\right]}{\left[\hbar \omega_y\frac{\omega_y}{\Omega_y} \left(n+\frac{1}{2}\right)+\hbar \omega_z\left(m+\frac{1}{2}\right)+ 2\Delta_c\right]^2}}+\\
+\frac{eR^2 \hbar^2}{\mu^*_x \gamma_0}\frac{1}{\sqrt{2\mu^*_x \beta_0}\sum_{nm}{F\left(\widetilde{\xi }_{nm}\right)}}\sum_{nm}{\frac{\ln \left[1+{\exp \left(\beta \widetilde{\xi}_{nm}\right)\ }\right]}{p{\left[\hbar \widetilde{\omega}_y \frac{\widetilde{\omega}_y}{\widetilde{\Omega}_y}\left(n+\frac{1}{2}\right)+\hbar \widetilde{\omega}_z \left(m+\frac{1}{2}\right)+2{\Delta }_v\right]}^2}} 
\]
`
<br>
`
\[
F\left(\xi_{nm}\right)=\int\limits^{\infty }_0 {\frac{dx}{\exp \left(x^2-\beta {\xi }_{nm}\right) +1}},
\]
\[
\widetilde{\xi }_{nm}=-\xi -\hbar \widetilde{\Omega}_y\left(n+\frac{1}{2}\right)-\hbar \widetilde{\omega}_z\left(m+\frac{1}{2}\right)+\Delta_0+\Delta_v
\]
`


Зависимость подвижности в относительны единица $\widetilde{\mu}=\mu(E)/\mu(0)$ от электрического поля

<img src="./images/fig_4_3_1.jpg" width="50%">



### Термоэдс в нанопроволоках Bi в попереченом постоянном электрическом поле

#### Термоэдс в массивных образцах

`
\[
\alpha_{xx}(H) = \frac{\gamma_{yx}}{T \sigma_{yx}}
\]
`

#### Термоэдс в низкоразмерных структурах

`
\[
\alpha_{xx}(H) = \frac{\gamma_{xx}}{T \sigma_{xx}}
\]
` 


`
\[
\gamma_{xx} = \int\limits_{- \infty }^{\infty}{\left\langle \hat{j_x}(t) \hat{Q}_x \right\rangle  dt} =
\frac{e \hbar^2 }{2 k_0 TV m_e^2} \sum_{\alpha}{\left( E_{\alpha} - \xi \right) k_x^2 \tau_{\alpha} n_{\alpha}\left( 1 - n_{\alpha} \right) }
\]
` 
<br>
`
\[
\sigma_{xx} = \int\limits_{- \infty }^{\infty}{\left\langle \hat{j}_x(t) \hat{j}_x \right\rangle  dt} =
\frac{e^2 \hbar^2 }{2 k_0 TV m_e^2} \sum_{\alpha}{k_x^2 \tau_{\alpha} n_{\alpha}\left( 1 - n_{\alpha} \right) }
\]
`


#### Термоэдс с учетом электронов и дырок

`
\[
\alpha _{xx} =-\frac{k_0}{e} \left\{\sum_{n,m}\left[\nu \frac{F_2 \left(\eta_{nm}^c \right)-\eta _{nm}^c F_1 \left(\eta_{nm}^c \right)}{\left(n+m+1+N_c \right)^2 } -\frac{F_2 \left(\eta_{nm}^v \right)-\eta_{nm}^v F_1 \left(\eta_{nm}^v \right)}{b\left(n+m+1+aN_c \right)^2 } \right] \right\}\times\\
\times \left\{\sum _{n,m}\left[\nu \frac{F_1 \left(\eta_{nm}^c \right)}{\left(n+m+1+N_c \right)^2 } +\frac{F_1 \left(\eta_{nm}^v \right)}{b\left(n+m+1+a N_c \right)^2 } \right] \right\}^{-1} 
\]
`
<br>
`
\[
a=\left(\frac{m_h }{m_c } \right)^{\frac{1}{2} } \left(\frac{\Delta E_c }{\Delta E_v } \right)^{\frac{3}{2} } ,\;
b=\frac{\Delta E_v }{\Delta E_c } , \\
\eta_{nm}^c =\beta \left[\Delta_c +\xi -\hbar \omega_c \left(n+m+1\right)\right], \\
\eta_{nm}^v =\beta \left[\Delta +\Delta_v -\xi -\hbar \omega_v \left(n+m+1\right)\right],
\]
`


`
\[
F_k (\eta )=\int\limits_0^{\infty }{\frac{ e^{x-\eta } x^k dx}{\left(1 + e^{x-\eta }\right)^2 }} 
\]
`

В частности для $k=0$
`
\[
F_0 (\eta)=\frac{1}{e^{-\eta}+1} 
\]
`

Для $k=1$ 
`
\[
F_1 (\eta )=\ln \left(1 + e^{\eta }\right)
\]
`

Для $k=1/2$ 
`
\[
F_{\frac{1}{2}} (\eta )=-\frac{\sqrt(\pi)}{2}\mathrm{Li}_{\frac{1}{2}}[-\exp(\eta)]
\]
`


#### Химический потенциал

`
\[
\nu \sqrt{\frac{m_e }{m_v } } \sum_{n,m}F_{\frac{1}{2}}\left(\eta_{nm}^c \right) =\sum_{n,m}F_{ \frac{1}{2}} \left(\eta_{nm}^v \right)
\]
`

Вырожденный электронный газ

`
\[
\xi -\hbar \omega_c =\Delta_0 +\Delta_v -\left(\hbar \omega_c +\hbar \omega_v \right), \left(\frac{\Delta_v }{\Delta_c } =\frac{\Delta E_c }{\Delta E_v } >1\right)
\]
`

`
\[
\alpha_{xx}^{(d)} =-\frac{k_0 }{e} \frac{\pi^3 }{3} \frac{1-\frac{1}{b\nu } \left(\frac{1+N_c }{1+aN_c } \right)^2 }{\Delta +\Delta_v -\left(\hbar \omega_c +\hbar \omega_v \right)}
\]
`

Термоэдс в случае невырожденного электронного газа

`
\[
\alpha_{xx}^{(nd)} =-\frac{k_0 }{e} \left\{2+\beta \left[\frac{1}{2} \ln \left( \nu^2 \frac{m_e }{m_h } \right) +\left(\hbar \omega_c +\hbar \omega_v -\Delta +\Delta_v +\Delta_c \right)\right]\right\}
\]
`


Зависимость удельной термоэдс квантовой проволоки от напряженности поперечного электрического поля

<img src="./images/fig_4_4_2.jpg" width="65%">