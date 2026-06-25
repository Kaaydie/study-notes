Jordan block
![[Pasted image 20260619124443.png]]
$D=\begin{bmatrix}-1 & 0 & 0 \\  0 & 2 & 0 \\  0 & 0 & 3\end{bmatrix}=[-1]\oplus[2]\oplus3=K_{1}(-1)\oplus K_{1}(2)\oplus K_{1}(3)$
jordan form
$\begin{bmatrix}2 & 1 & 0 & 0 \\  0 & 2 & 1 & 0 \\  0 & 0 & 2 & 1 \\  0 & 0 & 0 & 2\end{bmatrix}=K_{4}(2)$
jordan canonical form
$\begin{bmatrix}2 & 1 & 0 & 0 \\  0 & 2 & 0 & 0 \\  0 & 0 & 2 & 1 \\  0 & 0 & 0 & 2\end{bmatrix}=K_{2}(2)\oplus K_{2}(2)$
![[Pasted image 20260619125118.png]]

theory
![[Pasted image 20260619130150.png]]
example
$A=\begin{bmatrix}1 & 1 & 0 & 0 & 0 \\  0 & 1 & 0 & 0 & 0 \\  2 & 3 & -1 & -1 & 5 \\  0 & 0 & 0 & -4 & 12 \\  0 & 0 & 0 & -2 & 6\end{bmatrix}$
step 1 find eigen values
$\varphi(\lambda)=\det(A-\lambda I)$
$\det \begin{bmatrix}1-\lambda & 1 & 0 & 0 & 0 \\  0 & 1-\lambda & 0 & 0 & 0 \\  2 & 3 & (-1-\lambda) & -1 & 5 \\  0 & 0 & 0 & -4-\lambda & 12 \\  0 & 0 & 0 & -2 & 6-\lambda\end{bmatrix}$

![[Pasted image 20260619130806.png]]



=$(-1)^{3+3}·(-1-\lambda)·\begin{bmatrix}1-\lambda & 1 & 0 & 0 \\  0 & 1-\lambda & 0 & 0 \\  0 & 0 & -4-\lambda & 12 \\  0 & 0 & -2 & 6-\lambda\end{bmatrix}$
![[Pasted image 20260619130945.png]]
$(-1-\lambda)(1-\lambda)^{2}·\begin{bmatrix}-4-\lambda & 12 \\  -2 & 6-\lambda\end{bmatrix}$
too slow

$\varphi(\lambda)=\det(A-\lambda I)=0$

| $\lambda_{1}=-1$ | $\lambda_{2}=1$ | $\lambda_{3}=0$ | $\lambda_{4}=2$ |
| ---------------- | --------------- | --------------- | --------------- |
| a.m=1            | am=2            | am=1            | ak=1            |
| ·                | ·               | ·               | ·               |
| $K_{1}(-1)$      | ·               | $K_{1}(0)$      | $K_{1}(2)$      |
|                  | $K_{2}(1)$      |                 |                 |
$r_{0}=rank(A-I)^{0}=rank \ I=5$
$r_{1}=rank(A-I)^{1}=rank\underbrace{ \begin{bmatrix}0 & 1 & 0 & 0 & 0 \\  0 & 0 & 0 & 0 & 0 \\  2 & 3 & -2 & -1 & 5 \\  0 & 0 & 0 & -5 & 12 \\  0 & 0 & 0 & -2 & 5\end{bmatrix} }_{ A-I }$
$=rank\begin{bmatrix}2 & 3 & -2 & -1 & 5 \\  0 & 1 & 0 & 0 & 0 \\  0 & 0 & 0 & -2 & 5 \\  0 & 0 & 0 & -5 & 12 \\  0 & 0 & 0 & 0 & 0\end{bmatrix}\begin{matrix}    \\   \\  +r_{3}·\left( -\frac{5}{2} \right) \\  \end{matrix}$

$rank=\begin{bmatrix}2 & 3 & -2 & -1 & 5 \\  0 & 1 & 0 & 0 & 0 \\  0 & 0 & 0 & -2 & 5 \\  0 & 0 & 0 & 0 & -\frac{1}{2} \\  0 & 0 & 0 & 0 & 0\end{bmatrix}=4$
$\Delta_{1}=r_{0}-r_{1}=1$

$r_{2}=rank(A-I)^{2}=rank\begin{bmatrix}0 & 0 & 0 & 0 & 0 \\  0 & 0 & 0 & 0 & 0 \\  -4 & -4 & -4 & -3 & 1 \\  0 & 0 & 0 & 1 & 0 \\  0 & 0 & 0 & 1 & 1\end{bmatrix}=3$

$r_{0}=5,r_{1}=4,r_{2}=3$
$\Delta_{1}=r_{0}-r_{1}=1$ ·
$\Delta_{2}=r_{1}-r_{2}=1$ ·

$J=K_{1}(-1)\oplus K_{2}(1)\oplus K_{1}(0)\oplus K_{1}(2)$

example
$A=\begin{bmatrix}-6 & 10 & 7 & 7 \\  -2 & 3 & 3 & 2 \\  -2 & 3 & 2 & 3 \\  -1 & 2 & 1 & 1\end{bmatrix}$
$\varphi(\lambda)=\det(A-\lambda I)$
$\det \begin{bmatrix}-6-\lambda & 10 & 7 & 7 \\  -2 & 3-\lambda & 3 & 2 \\  -2 & 3 & 2-\lambda & 3 \\  -1 & 2 & 1 & 1-\lambda\end{bmatrix}$ 
=$\lambda^{4}=0$
$\lambda=0 \ a.m.=4$

```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2026.6.19 - 13.26pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```
$r_{0}=rank(A-0·I)^{0}=4$
$r_{1}=rank(A)^{1}=$
$=rank=\begin{bmatrix}-6 & 10 & 7 & 7 \\  -2 & 3 & 3 & 2 \\  -2 & 3 & 2 & 3 \\  (-1) & 2 & 1 & 1\end{bmatrix}\begin{matrix}+r_{4}·(-6) \\  +r_{4}·(-2) \\  +r_{4}·(-2) \\  ·(-1)\end{matrix}$

=$rank\begin{bmatrix}1 & -2 & -1 & -1 \\  0 & -2 & 1 & 1 \\  0 & -1 & 1 & 0 \\  0 & -1 & 0 & 1\end{bmatrix}\begin{matrix}  \\   r_{2}\iff r_{4} \\  \\   ·(-1)   \end{matrix}$

rank=3
$\Delta_{1}=r_{0}-r_{1}=1$

```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2026.6.19 - 13.32pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```
$J=K_{4}(0)$
$\lambda_{1}=1,\lambda_{2}=2,\lambda_{3}=3$


```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2026.6.19 - 13.34pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```
$\vec{b}_{3}=?$
$(A-I)^{3}·\vec{b}=\vec{0}$
$\vec{b}_{2}=(A-I)·\vec{b}_{3}$
$\vec{b}_{1}=(A-I)·\vec{b}_{2}$
$(A-I)^{1}\vec{b}=0$
$\vec{b}_{4}$

$(A-I)^{1}·\vec{b}=0$


---

# simple example
$A=\begin{bmatrix}1 & 0 & 0 \\  -15 & 12 & -8 \\  -18 & 12 & -8\end{bmatrix}$
step 1 characteristic polynomial
$\varphi(\lambda)=\det(A-\lambda I)$
$=\begin{bmatrix}1-\lambda & 0 & 0 \\  -15 & 12-\lambda & -8 \\  -18 & 12 & -8-\lambda\end{bmatrix}$
$=(1-\lambda)((12-\lambda)(-8-\lambda)+96)=$
$=(1-\lambda)(-96-12\lambda+8\lambda+\lambda^{2}+96)$
$=\lambda(1-\lambda)(\lambda-4)=0$
$\lambda_{1}=0,\lambda_{2}=1,\lambda_{3}=4$
·              ·           ·
$D=\begin{bmatrix}0 & 0 & 0 \\  0 & 1 & 0 \\  0 & 0 & 4\end{bmatrix}$

step 2 find eigen vectors
$\lambda_{1}=0$
$(A-\lambda I)·\vec{x}=\vec{0}$
$A\vec{x}=\vec{0}$
$\begin{bmatrix}1 & 0 & 0 \\  -15 & 12 & -8 \\  -18 & 12 & -8\end{bmatrix}\begin{matrix} \\  r_{1}·15 \\  r_{1}·18\end{matrix}$

$\begin{bmatrix}1 & 0 & 0 \\  0 & 12 & -8 \\  0 & 12 & -8\end{bmatrix}\begin{matrix} \\  :12 \\  +r_{2}·(-1)\end{matrix}$

   $x_{1} \ x_{2} \ x_{3}$
~$\begin{bmatrix}1 & 0 & 0 \\  0 & 1 & -\frac{2}{3} \\  0 & 0 & \underbrace{ 0 }_{ t }\end{bmatrix}$

$\vec{x}=\begin{bmatrix}0 \\  \frac{2}{3}t \\  t\end{bmatrix}t\in \mathbb{C} \setminus [0]$
$\lambda_{1}=0$
·
$\begin{bmatrix}0 \\  2 \\  3\end{bmatrix}$

---
$(A-\lambda I)·\vec{x}=\vec{0}$
$(A-I)·\vec{x}=0$
$r_{1}\iff r_{3} \begin{bmatrix}0 & 0 & 0 \\  -15 & 11 & -8 \\  -18 & 12 & -9\end{bmatrix}\begin{matrix} \\   \\  +r_{2}·(-1)\end{matrix}$

~$\begin{bmatrix}-3 & 1 & -1 \\  -15 & 11 & -8 \\  0 & 0 & 0\end{bmatrix}\begin{matrix} \\  +r_{1}·(-5) \\  \end{matrix}$

~$\begin{bmatrix}-3 & 1 & -1 \\  0 & 1 & -\frac{1}{2} \\  0 & 0 & 0\end{bmatrix}\begin{matrix}+r_{2}·(-1) \\   \\  \end{matrix}$

~$\begin{bmatrix}-3 & 0 & -\frac{1}{2} \\  0 & 1 & -\frac{1}{2} \\  0 & 0 & 0\end{bmatrix}$
$x_{1} \ x_{2} \ x_{3}$
~$\begin{bmatrix}1 & 0 & \frac{1}{6} \\  0 & 1 & -\frac{1}{2} \\  0 & 0 & \underbrace{ 0 }_{ t }\end{bmatrix}$

$\vec{x}=\begin{bmatrix}-\frac{1}{6}t \\  \frac{1}{2}t \\  t\end{bmatrix},t\in   \mathbb{C}\setminus[0]$
$\lambda_{2}=1$
·
$\begin{bmatrix}-1 \\  3 \\  6\end{bmatrix}$

---

$\lambda_{3}=4$
$(A-4I)·\vec{x}=\vec{0}$

~$\begin{bmatrix}1 & 0 & 0 \\  0 & 1 & -1 \\  0 & 1 & -1\end{bmatrix}$

$\vec{x}=\begin{bmatrix}0 \\  t \\  t\end{bmatrix}$

$\lambda_{3}$
$\begin{bmatrix}0 \\  1 \\  1\end{bmatrix}$


transition matrix

$P=\begin{bmatrix}0 & -1 & 0 \\  2 & 3 & 1 \\  3 & 6 & 1\end{bmatrix}$

---

# next example

$A=\begin{bmatrix}-4 & -5 & 6 & 6 \\  0 & -1 & 0 & 0 \\  0 & 0 & 1 & 0 \\  -3 & -5 & 8 & 5\end{bmatrix}$
