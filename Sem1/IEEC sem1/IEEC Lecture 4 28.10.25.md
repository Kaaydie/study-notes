# part 1
FORMULA FOR POWER
ENERGY
CAPACITY OF BATTERY
ENERGY ACUMULATED BY BATTERY(IN WAT/HOURS)

2 batteries in series = 2 * Voltage
2 batteries paraller = 2 * the capacity

---
![[git-sync/Sem1/IEEC sem1/Pasted image 20251028124250.png]]
$I= \frac{E_{0}-U}{R_{INT}}$
$I=\frac{E_{0}}{R_{INT}}-\frac{1}{R_{INT}}U$

$I=-\frac{1}{R_{INT}}U+\frac{E_{0}}{R_{INT}}$
$\uparrow$              $\uparrow$ $\uparrow$
y             A    X          b


---
![[git-sync/Sem1/IEEC sem1/Pasted image 20251028125614.png]]

$R_{1}=3\Omega$
$R_{2}=7\Omega$
$E=12V$
$J=2A$

$\underline{U_{R_{2}}-U_{I}-E=0}$
$U_{J}=U_{R_{2}}-E=JR_{2}-E=2V$
$I_{E}=I_{R_{1}}+J$

$P_{y}=U_{J} \cdot J=4W$
$P_{E}=E\cdot J_{E}=72W$

---
![[git-sync/Sem1/IEEC sem1/Pasted image 20251028130325.png]]
$U_{2}=I_{1}R_{2}=6V$
$R_{1}=\frac{U_{1}}{I_{1}}=\frac{4}{1.5}=2.67\Omega$
$P_{R_{2}}=9W$
$P_{R_{2}}=I_{1}^2\cdot R_{2}$
$I_{1}=\sqrt{ \frac{P_{R_{2}}}{R_{2}} }=1.5A$

---

## Principles and theorems of electric circuits, Thevenin’s & Norton’s theorems

the principle of superposition
![[git-sync/Sem1/IEEC sem1/Pasted image 20251028130616.png]]

---
![[git-sync/Sem1/IEEC sem1/Pasted Image 20251028130851_532.png]]

$\underline{U_{L}=U_{L}^E+U_{L}^I}$

![[git-sync/Sem1/IEEC sem1/Pasted image 20251028131318.png]]
$U_{L}^E=E \frac{R_{2}}{R_{1}+R_{2}}$

![[git-sync/Sem1/IEEC sem1/Pasted image 20251028131457.png]]
$U_{L}^I=I \frac{R_{1}}{R_{1}+R_{2}}*R_{2}$

---
![[git-sync/Sem1/IEEC sem1/Pasted image 20251028133131.png]]
S = Semens
current source:($J_{S}=4A$ $G_{t}=2S=0.5\Omega$)
Voltage source:($E_{0}=?$$R_{1}=1\Omega$)
are connected in paraller ("+" with "+" )
Find the open-circuit voltage of the voltage source,in V, for which there is no power transfer between the sources

$I=I^{E_{0}}+I^{J_{S}}$

$I^{E_{0}}=\frac{E_{0}}{R_{S}+R_{t}}=\frac{E_{0}}{1.5}$

$I^{J_{S}}=-J_{S} \frac{R_{S}}{R_{S}+R_{t}}=-\frac{4}{3}A=-1.33A$

$I=I^{E_{0}}+I^{J_{S}}$
$\frac{E_{0}}{1.5}-\frac{4}{3}=0$
$E_{0}=2V$

---

Find power of the voltage source (value in W and sign,"+"if supplied). 
$E=10V$
$J=2A$
$R_{1}=4\Omega$
$R_{2}=9\Omega$
$R_{3}=9\Omega$

$P_{E}=EI_{E}$
$I_{E}=I_{E}^J+I_{E}^E$ 
![[git-sync/Sem1/IEEC sem1/Pasted image 20251028133818.png]]
$I_{E}^J=-J=-2A$

![[git-sync/Sem1/IEEC sem1/Pasted image 20251028134149.png]]
$I_{E}^E=\frac{E}{12.5}=0.8A$

$I_{E}=I_{E}^J+I_{E}^E=-12A$

---
---
# Part 2


![[ToLC sem1/Pasted image 20251028141128.png]]

Increment analysys
![[ToLC sem1/Pasted image 20251028141428.png]]
so I is not revelant

![[ToLC sem1/Pasted image 20251028141523.png]]
$\Delta U_{L}=\underline{\Delta U_{L}^{\Delta E}}+\Delta U_{L}^{\Delta I}$
$\Delta U_{L}=\Delta E \frac{R_{2}}{R_{1}+R_{2}}$
---
EMF - electromotive force
The emf has increased its value 6 times (up to 6E).
Calculate increment (value and sign) of the current I.
$E=3V$
$J=6A$
$R_{1}=3\Omega$
$R_{2}=6\Omega$
$R_{3}=3\Omega$

![[ToLC sem1/Pasted image 20251028142300.png]]

$\Delta I=\Delta I^{\Delta E}+\Delta I^{\Delta J}=0$
$\Delta E=5E=15$
$\Delta J^{\Delta E}= \frac{\Delta E}{5}\cdot \frac{6}{9}=2A$

---
Two-terminal subcircuit (one-port subcircuit)
passive circuit only containst resistors
active contains at least a 1 source of energy

## Pasive 2 terminal subcircuit
![[ToLC sem1/Pasted image 20251028143427.png]]
![[ToLC sem1/Pasted image 20251028143749.png]]
$R_{12}=\frac{R_{1}R_{2}}{R_{1}+R_{2}+R_{0}}$
$R_{10}=\frac{R_{1}R_{6}}{R_{1}+\frac{R_{2}}{R_{0}}}$

## Active 2 terminal circuit
![[ToLC sem1/Pasted Image 20251028144446_081.png]]
$E_{0}=E_{0}^E+E_{0}^y$

![[ToLC sem1/Pasted image 20251028145022.png]]
$E_{0}^E=E$

![[ToLC sem1/Pasted image 20251028145307.png]]
$E_{0}^I=IR_{1}$

$E_{0}=E_{0}^E+E_{0}^I$
![[ToLC sem1/Pasted image 20251028145705.png]]
$R_{t}=R_{1}+R_{2}$
$E_{0}=E+IR_{2}$

---

![[ToLC sem1/Pasted image 20251028150113.png]]
Find the Thevenin-equivalent resistance, in $\Omega$
$E=10V$
$R_{1}=3\Omega$
$R_{2}=6\Omega$
$R_{3}=8\Omega$
![[ToLC sem1/Pasted image 20251028150348.png]]
ANS $6\Omega$

---
A source with an open-circuit voltage of 6V and a short-circuit current of 3A is connected to a 4Ω load.
What resistance, in Ω, should be connected in series to limit the power absorbed by the load to 1W?

$P_{R_{L}}=1W$ (max)

$P_{R_{L}}=1W = I^2\cdot R_{L}$
$I=\sqrt{ \frac{1}{4} }=0.5A$
$U_{R_{1}}=$
![[ToLC sem1/Pasted image 20251028151846.png]]

---
Two partical sources characterized by the following parameters:
$1. E_{0}=4V, R=7Ω$
$2.J_{S}=2A, G_{S}=0.1S$
are connected in series,as shown. Find current, in A, that flows through the 7Ω load resistance
![[ToLC sem1/Pasted image 20251028152345.png]]

---

![[git-sync/Sem1/IEEC sem1/Pasted image 20251104122611.png]]