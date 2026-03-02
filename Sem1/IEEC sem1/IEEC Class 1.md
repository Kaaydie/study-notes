

EX. 1
Voltage divider

![[git-sync/Sem1/IEEC sem1/Pasted image 20251027101629.png]]

$I=\frac{U_{IN}}{R_{1}+R_{2}}$
$U_{2}=I*R_{2}=U_{IN}* \frac{R_{2}}{R_{1}+R_{2}}=k*U_{IN}=\frac{U_{IN}}{n}$
$[V]= [V] \frac{[\Omega]}{[\Omega]+[\Omega]=[V]}$
$n=\frac{1}{k}$

$U_{2}=f(U_{IN},R_{1},R_{2})=?$
$R_{1,2}\epsilon<0,inf)$
$k\epsilon<0,1>$
$U_{2}\epsilon<0,U_{IN}>$
$n\epsilon<1,inf)$

Homework 
check what is formula for u1
check units for k

EX. 2
Voltage divider with load
![[git-sync/Sem1/IEEC sem1/Pasted image 20251027103120.png]]

$U_{2}=U_{IN} * \frac{R_{X}}{R_{1}+R_{X}} \frac{:R_{X}}{:R_{X}}=$
$=U_{IN} \frac{1}{\frac{R_{1}}{R_{x}}+1}=$
$\frac{1}{R_{x}}=\frac{1}{R_{L}}+\frac{1}{R_{2}}\to R_{X}=$
$R_{X} = \frac{R_{L}R_{2}}{R_{L}+R_{2}}$

$U_{2}=U_{IN} \frac{R_{2}R_{L}}{R_{1}R_{2}+R_{1}R_{L}+R_{2}R_{L}}$

$U_{IN} \frac{1}{\left( \frac{1}{R}+\frac{1}{R_{2}} \right)R_{2}+1}=$
$=U_{IN} \frac{1}{\frac{R_{1}}{R_{L}}+\frac{R_{1}}{R_{2}}+1}$

$U_{2}=U_{IN} \frac{R_{2}*∞}{R_{1}R_{2}+R_{1}*∞+R_{2}*∞}=$
$U_{IN}= \frac{∞}{R_{1}R_{2}+∞+∞}=$
$U_{IN}= \frac{∞}{∞}$

shit is too fast to note lol

EX.3
Current divider
![[git-sync/Sem1/IEEC sem1/Pasted image 20251027103923.png]]
$I_{2}= f(I_{IN},R_{1},R_{2})=?$
$U=I_{IN}*R_{X}=I_{IN} \frac{R_{1}R_{2}}{R_{1}+R_{2}}$
$I_{2}= \frac{U}{R_{2}}= \frac{I_{IN}\frac{R_{1}R_{2}}{R_{1}+R_{2}}}{R_{2}}=$
$= I_{IN} \frac{R_{1}}{R_{1}+R_{2}}$
$=U_{IN} \frac{R_{2}}{R_{1}+R_{2}}$

$G_{1}=\frac{1}{R_{1}}$
$G_{2}=\frac{1}{R_{2}}$

$I_{IN}=\frac{G_{2}}{G_{1}+G_{2}}$


## EX.4
![[git-sync/Sem1/IEEC sem1/Pasted image 20251027110353.png]]
NiMH cell
$1.2V / (2000mAh)$
	Rated "Capacity"
"Nominal parameters"
(discharging)

$U*i=P$
$P=\frac{W}{t}$

$\underline{W}=P*T=U*I*t=U*Q$
$I*t=Q$

$W_{DISCH}=U*Q=1.2V*2000mA*h=2.4V*A*h$
$=\underline{2.4Wh}$
a) Normal charging
1.5V 200mA
12h
<hr>
b) Fast charging
1.6V 2A 2.5H

ENERGY EFFICIENCY??

$n = \frac{W_{disch/}}{W_{CH}}*100\%$
a)$W_{CH}=1.5V*200mA*12h=3.6Wh$
$n=\frac{2.4Wh}{3.6Wh}*100\%=\frac{2}{3} =67\%$

b) $W_{CH}=1.6V*2A*2.5h=8Wh$
$n= \frac{2.4Wh}{8Wh}*100\%=30\%$

## EX.4
Carnot (?) Cycle
Diesel ≈40%
Gasoline ≈25% (20-30%)

## EX.5
Calculate votage messurement error coused by volt meter connection
a) IDEAL DC (V)
b) $R_{v}=10*R$
c) $R_{V}=2*R$

Ref. case
![[git-sync/Sem1/IEEC sem1/Pasted image 20251027110949.png]]
$U_{2REF}=U_{IN}* \frac{R}{R+R}= \frac{U_{IN}}{2}=\underline{5V}$

a)
![[git-sync/Sem1/IEEC sem1/Pasted image 20251027111133.png]]
Absolute error:
$\Delta U_{V}=U_{V}-U_{2REF}=0V$
Percentage
(Relative) Error:
p%=$\frac{\Delta U_{V}}{U_{2REF}}*100\%=0\%$
<hr>

b)
![[git-sync/Sem1/IEEC sem1/Pasted image 20251027112154.png]]
$U_{V}=\frac{U_{IN}R^2}{R*R+R*R_{V}+R*R_{V}}=$
$=U_{IN} \frac{R_{v}}{R+2R_{V}}$

$=U_{IN} \frac{R_{v}}{R+2R_{V}} \frac{:R_{L}}{:R_{L}}$

$U_{v}=U_{IN} \frac{1}{\frac{R}{R_{v}}+2}=10V \frac{1}{\frac{R}{10*R}+2}$$=\frac{10V}{2.1}≈4.76$
$\Delta V=-0.24V$
P%=$-\frac{0.24V}{5V}*100\%=-4.8\%$
<hr>
c)
$R_{V}=2R= \frac{20M\Omega}{1}$
$U_{V}=10V \frac{\frac{1}{10M\Omega}}{20M\Omega}+2=$
$\frac{10V}{2.5}=4V$
$\Delta U_{V}=4V-5V=-1V$
P%$=-\frac{1V}{5V}*100\%=\underline{-20\%}$
end


