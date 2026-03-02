# Superposition principle
## Ex.1
![[git-sync/Sem1/IEEC sem1/Pasted image 20251117101828.png]]
$$
\begin{align}
 & I=\frac{U}{R}=\frac{0V}{0Ω}=\frac{0}{0}A??? \\
 & +I_{1}-I_{2}-I=0\to I=I_{1}-I_{2} \\
 & -I_{1}+I_{2}+I=0\to I=I_{1}-I_{2} \\
 & I=\frac{U_{3}}{R_{3}}(1) \\
 & KVL: +E_{1}-U_{3}-E_{2}-\overbrace{ U }^{ 0V }=0 \to U_{3}=E_{1}-E_{2}UU
\end{align}

$$
as homework solve this example using superposition  principle

---
## Ex.2
$$
\begin{align}
 & I=\underbrace{ I^{I} }_{ E }+\underbrace{ I^{II} }_{ J } \\
 & I^{I}=\frac{E}{2R}=\frac{30V}{40Ω}=0.75A \\
 & I^{II}=\frac{J}{2}=0.25A  \\
 & I=\underbrace{ I^{I} }_{ E }+\underbrace{ I^{II} }_{ J }=0.75A+0.25A=1A
\end{align}
$$
![[git-sync/Sem1/IEEC sem1/Pasted image 20251117102655.png]]

---
# Incremental analysis (Linear)
## Ex.1
Voltage source E increased its value 3 times
Calculate incriment of the current I
$E\to 3E$
$\Delta I=?$

$$
\begin{align}
 & E=10V \\
 & J=2.5A \\
 & \Delta I=I^{A}-I^{B}  \\
 &  \\
 & I.A. \\
 & \text{step 1}   \\
 & CIR \to \Delta \\
 & E \to \Delta E \\
 & J \to \Delta J \\
 & U \to \Delta U \\
 & I \to \Delta I \\
 & R \to R \\
 &  \\
 & \Delta E=3E-E=2E=20V \\
 & \Delta J=0A \\
 &  \\
 & \text{Step 2. Solution} \\
 & \Delta I_{E}=\frac{\Delta E}{R_{1}+R_{2}||R_{3}}= \\
 & \Delta I=\Delta I_{E} \frac{R_{2}}{R_{2}+R_{3}}= \\
 & =0.86A \frac{80Ω}{360Ω} = \\
 & =0.28A
\end{align}
$$
![[git-sync/Sem1/IEEC sem1/Pasted image 20251117104250.png]]

---
## Ex.2
Value of the votage source decreased by 20%,
calulate the incriment of the current source in order to compensathe the change of the current I
$E\to-20\%$
$\Delta J=? \to I=const$

$$
\begin{align}
 & \Delta I=0A \\
 & \Delta E=0.8E-E=-0.2E=-4V \\
 &  \\
 & \text{KVL:} \\
 & +\Delta JR+\Delta E-\Delta U_{J}+\Delta JR=0 \\
 & 2\Delta JR+\Delta E-\Delta U_{J}=0 \\
 & \\
 & \text{super possition principle} \\
 & \Delta I=\overbrace{ \Delta I^{I} }^{ \Delta E }+\Delta \overbrace{ I^{II} }^{ \Delta J }=0A  \\
 &  \\
 & \Delta I^{I}=-0.04A=-40mA \\
 & \Delta I^{II}=\frac{\Delta J}{2} \\
 & -40mA+\frac{\Delta J}{2}=0 \\
 & \Delta J=80mA
\end{align}
$$
![[git-sync/Sem1/IEEC sem1/Pasted image 20251117110338.png]]

---
## Ex.3 
$U_{1}\to x 2$
$\Delta U_{2}=?$

$$
\begin{align}
 & \Delta E=0V  \\
 & \Delta U_{1}=2U_{1} -U_{1}=U_{1}=20V \\
 &  \\
 & R_{x}= \frac{3R·2R}{5R}=\frac{6}{5}R=1.2R \\
 &  \\
 & \Delta U=\Delta U_{1} \frac{1.2R}{2R}=0.6\Delta U_{1} \\
 & \Delta U_{2} = \frac{0.6·\Delta U_{1}}{2}=0.3·\Delta U_{1}= \\
 & =0.3·20V=6V
\end{align}
$$
![[git-sync/Sem1/IEEC sem1/Pasted image 20251117111153.png]]

---

# Power:
## Ex.1
$J=?\neq 0A$
$P_{J}=0W$
ASC
$P=U_{J}·I$
ASC:$$
\begin{align}
 & P>0W & DEL. \\
 & P<0W & ABS. \\
 & P=0W
\end{align}
$$
PSC:$$
\begin{align}
 & P>0W  & ABS \\
 & P<0W  & DEL \\
 & P=0W
\end{align}
$$
$$
\begin{align}
 & P=U_{J}·I=\overbrace{ U_{J} }^{ =0 }·\overbrace{ J }^{ \neq0A }=0W \to U_{J}= \\
 & J=\overbrace{ J^{I} }^{ 2E }+\overbrace{ J^{II} }^{ E } \\
 & I= \frac{2E}{R+\frac{R}{2}}=\frac{4}{3} \frac{E}{R}= \\
 & \frac{4·20V}{3·10Ω}=\frac{8}{3}A \\ 
 & J^{I}=-\frac{4}{3}A \\
 &  \\
 & J^{II}=? \\
 & I_{1}=\frac{E}{R+\frac{R}{2}} \\
 & J^{II}=-\frac{2}{3}A
\end{align}
$$
![[Pasted image 20251117112903.png]]
