Ex.1 
![[Pasted image 20251103102703.png]]
ICCL

$$
\begin{align}
 & n_{1}:I_{1}+I_{A}=I_{2} \\
 & n_{2}:I_{3}=I_{A}+I_{4} \\
 & I_{A}=I_{2}-I_{1}=I_{4}-I_{3}(1)  \\
  & --- \\
 & I_{1}= \frac{4R_{1}}{4R_{1}+R_{1}}=\frac{4}{5}I= 0.8I \\
 & I_{2}=I \frac{9R_{2}}{9R_{2}+R_{2}}=0.9I \\
 & I_{A}=0.9I-0.8I=0.1I (2)  \\
 & --- \\
 & I= \frac{U}{R_{A}+R_{B}} \\
 & --- \\
 & R_{A}=\frac{R_{1}\cdot R_{1}}{R_{1}+4R_{1}}=\frac{4}{5}R_{1} & R_{B}=\frac{R_{2}\cdot 9R_{2}}{R_{2}+9R_{2}}=0.9R_{2} \\
 & I= \frac{U}{R_{A}+R_{B}}=\frac{U}{0.8R_{1}+0.9R_{2}} \\
 & =\frac{16V}{0.8\cdot 25\Omega+0.9\cdot 18\Omega} \\
 & =0.44A
\end{align}
$$
---
Ex.2
Calculate output voltage of voltage adder

basic method/general method
KVL (Kirov law),
KCL, ()
OHM's L. (ohms law)

Data: $U_{1},U_{2},R,R_{2}$
Unkown vars: $\underline{U_{out}}=?$
$I_{1},I_{2},I,U_{R_{1}},U_{R_{2}}$ 
![[Pasted image 20251103105920.png]]



$$
\begin{align} \\
 & \text{KCL: n-nodes}  \\
 & \text{indep. eq.: n-1=} \\
 & (1): +I_{2}+I_{1}-I=0  \ (1) \\
 & (2): +I-I_{1}-I_{2}=0 \\
 & --- \\
 & \text{KVL: L-loops:3} \\
 & \text{L-1 indep. eq.2} \\
 & --- \\
 & I:+U_{2}-U_{R_{2}}-U_{OUT}=0 \ (2)\\
 & II:+U_{1}-U_{R_{1}}-U_{OUT}=0 \ (3) \\
 & --- \\
 & U_{R_{2}}=I_{2}\cdot R \ (4) \\
 & U_{R_{1}=I_{1}}\cdot R \ (5) \\
 & U_{OUT}=I*R_{L} \ (6) \\
 & --- \\
 & U_{OUT}=I\cdot R_{L}=(I_{1}+I_{2})R_{L}= \left( \frac{U_{R_{1}}}{R}+\frac{U_{R_{2}}}{R} \right)R_{L}=  \\
 & \left( \frac{U_{1}-U_{OUT}}{R}+\frac{U_{2}-U_{OUT}}{R} \right)R_{2} /\cdot \frac{R}{R_{L}} \\
 & \frac{R}{R_{2}}\cdot U_{OUT}=U_{1}-U_{OUT}+U_{2}-U_{OUT}=U_{1}+U_{2}-2U_{OUT} \\
 & U_{OUT}\left( \frac{R}{R_{L}}+R \right)=U_{1}+U_{2} \\
 & U_{OUT}= \frac{U_{1}+U_{2}}{\left( \frac{R}{R_{2}} +2\right)}= \\
 & = \frac{10V+(-20V)}{\frac{20K\Omega}{100K\Omega}+2}=\frac{-10V}{2.2} \\
 & ≈ \underline{-4.54V}
\end{align}
$$
---
Ex. 3
Average value of 2 numbers
$U_{OUT}=\frac{U_{1}+U_{2}}{2}$
Idea 1) R=0Ω - Short circuit (2 resistors) cheaper?
Idea 2) $R_{2}\to ∞$ - open circuit (1 resistor)

.1. Verification
![[Pasted image 20251103111500.png]]
2.Verification
![[Pasted image 20251103111934.png]]
$$
\begin{align}
 & U_{1}-U_{R}-U_{OUT}=0 \\
 & U_{OUT}=U_{1}-U_{R} \\
 & U_{OUT}=U_{1}-I\cdot R \\
 & I= \left( \frac{U_{1}-U_{2}}{2R} \right)=\frac{U}{2R} \\
 & U_{OUT}=U_{1} -\left( \frac{U_{1}-U_{2}}{2R} \right)\cdot R=U_{1}-\frac{U_{1}}{2}+\frac{U_{2}}{2} \\
 & = \underline{\frac{U_{1}}{2}+\frac{U_{2}}{2}} \\
 & 
\end{align}
$$
HOMEWORK: 
![[Pasted image 20251103112358.png]]

---
Ex.4 Find value of current I
a perfect short circuit is a 2 terminal element where voltage is always 0 regardless of current
resistor=0Ω equvilient to short circuit
![[Pasted image 20251103114325.png]]