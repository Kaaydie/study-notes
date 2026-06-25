$T:V\to W \ ,\vec{u},\vec{v}\in V,\alpha\in \mathbb{K}$
$T(\vec{u}+\vec{v})=T(\vec{u})+T(\vec{v})$
$T(\alpha·\vec{u})=\alpha·T(\vec{u})$

$T:\mathbb{R}^{n}\to \mathbb{R}^{m}-\text{lin. trans}$
$T(\vec{v})=A·\vec{v}$
$A_{m\times m}$

---
kernel and image fix
$ker(T)=\{ \vec{v}\in V:T(\vec{u})=\vec{0} \}$
$im(T)=\{ \vec{u}\in \}$

---
# 1
$F:\mathbb{R}^{2}\to \mathbb{R}^{2}$
$F(x_{1},x_{2})=(Bx_{1},x_{1}+x_{2})$
check both axioms
$\alpha=\mathbb{R}$
$\vec{x}=(1,2) \ F(\vec{x})=(3,3)$
$\vec{x}=(-3,1) \ F(\vec{x})=(-9,-2)$
$\vec{u}=(u_{1},u_{2})\in R^{2}$
$\vec{v}=(v_{1},v_{2})\in R^{2}$
axiom 1
$T(\vec{u}+\vec{v})=T(u_{1}+v_{1},u_{2}+v_{2})=(3(u_{1}+v_{1}),(u_{1}+v_{1})+(u_{2}+v_{2}))$
$=(3u_{1}+3v_{1},u_{1}+u_{2}+v_{1}+v_{2})$=
$=(3u_{1},u_{1}+u_{2})+(3v_{1},v_{1}+v_{2})=T(\vec{u})+T(\vec{v})$
axiom 2
$T(\alpha·\vec{u})=T(\alpha u_{1},\alpha u_{2})=(3\alpha u_{1},\alpha u_{2})$
=$\alpha·(3u_{1},u_{1}+u_{2})=\alpha·T(\vec{u})$
Matrix of transformation
- determine the basis $\begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}$
- $F(e_{1})=3,1$
- $F(e_{2})=0,1$
$\begin{bmatrix}3 & 0 \\ 1 & 1\end{bmatrix}$
$F((7,-8))=\begin{bmatrix}3 & 0 \\ 1 & 1\end{bmatrix}·\begin{bmatrix}7 \\ -8\end{bmatrix}=\begin{bmatrix}21 \\ -1\end{bmatrix}$
inverse $\det(A)=3$
$A^{-1}=\frac{1}{3}\begin{bmatrix}1 & 0 \\ -1 & 3\end{bmatrix}$
$F^{-1}(\vec{y})=A^{-1}·\vec{y}$
# 2
$F:R^{2}\to R^{3}$
$F(x_{1},x_{2})=(x_{1}+x_{2},0,x_{1}·x_{2})$
its not
$\vec{u},\vec{v}\in \mathbb{R}^{2}$
$F(\vec{u}+\vec{v})=F((u_{1}+v_{1})+(u_{2}+v_{2}),0,(u_{1}+v_{1})·(u_{2}+v_{2}))=$
$F(\vec{u})+F(\vec{v})=(u_{1}+u_{2},0,u_{1}·u_{2})+(v_{1}+v_{2},0,v_{1}·v_{2})=$
=$(u_{1}+u_{2}+v_{1}+v_{2},0,(u_{1}u_{2}+v_{1}v_{2}))$ is diffrent
# 3
$F:\mathbb{R}^{3}\to R^{2}$
$F(x_{1},x_{2},x_{3})=(x_{2}-x_{1},x_{3}-x_{2})$

$\vec{u},\vec{v}\in \mathbb{R}^{3}$
$\vec{u}=(u_{1},u_{2},u_{3})$
$\vec{v}=(v_{1},v_{2},v_{3})$
addition
$F(\vec{u}+\vec{v})=F(u_{1}+v_{1},u_{2}+v_{2},u_{3}+v_{3})=$
=$((u_{2}+v_{2})-(u_{1}+v_{1}),(u_{3}+v_{3})-(u_{2}+v_{2}))$=
=$((-u_{1}+u_{2})+(-v_{1}+v_{2}),(u_{3}-u_{2})+(v_{3}-v_{2}))$=
=$(u_{2}-u_{1},u_{3}-u_{2})+(v_{2}-v_{1},v_{3}-v_{2})$
multiplication by scalar
$F(\alpha·\vec{u})=(\alpha·u_{1},\alpha·u_{2},\alpha ·u_{3})$=
=$(\alpha·u_{2}-\alpha·u_{1},\alpha·u_{3}-\alpha·u_{2})$=
=$\alpha(u_{2}-u_{1},u_{3}-u_{2})$
matrix of transofmration
$A=\begin{bmatrix}-1 & 1 & 0 \\ 0 & -1 & 1\end{bmatrix}$
# 4
$F:R^{3}\to R^{3}$
$F(x_{1},x_{2},x_{3})=(x_{1},|x_{2}|,x_{3})$
not a linear transformation
# 5
$F:R^{n}\to R^{n}$
$F(x_{1},\dots,x_{n})=(x_{n},x_{n-1},\dots,x_{2},x_{1})$
$\vec{u}=(u_{1},\dots,u_{n})$
$\vec{v}=(v_{1},\dots,v_{n})$

$F(\vec{u}+\vec{v})=(u_{n}+v_{n},u_{n-1}+v_{n-1},\dots,u_{2}+v_{2},u_{1}+v_{1})=F(\vec{u})+F(\vec{v})$
$F(\alpha ·\vec{u})=(\alpha u_{n},\alpha u_{n-1},\dots,\alpha u_{2},\alpha u_{1})=$
=$\alpha(u_{n},u_{n-1},\dots,u_{2},u_{1})$
matrix of transformation
$A=\begin{bmatrix}0 & 0 & \dots & 0 & 1 \\ 0 & 0 & \dots & 1 & 0 \\ \vdots & \vdots & \dots & \vdots & \vdots  \\ 0 & 1 & \dots & 0 & 0 \\ 1 & 0 & \dots & 0 & 0\end{bmatrix}$

# image of matrix transformation

$L_{1}:\mathbb{R}^{2}\to \mathbb{R}^{2} \ L_{1}((x_{1},x_{2}))=(2x_{1}-4x_{2},x_{1}+2x_{2})$
$L_{2}:\mathbb{R}^{2}\to \mathbb{R}^{2} \ L_{2}((x_{1},x_{2}))=(x_{1}-x_{2},-x_{2})$

$L_{1} \odot L_{2}$
$(L_{1}\odot L_{2})(\vec{v})$
$\vec{v}=(-1,1)$

$L=L_{1} \odot L_{2} :\mathbb{R}^{2}\to \mathbb{R}^{2}$
$A_{1}=\begin{bmatrix}2 & -4 \\ 1 & 2\end{bmatrix} A_{2}=\begin{bmatrix}1 & -1 \\ 0 & -1\end{bmatrix}$

$A=\begin{bmatrix}2 & -4 \\ 1 & 2\end{bmatrix}·\begin{bmatrix}1 & -1 \\ 0 & -1\end{bmatrix}=\begin{bmatrix}2 & 2 \\ 1 & -3\end{bmatrix}$

$(L_{1}\odot L_{2})(\vec{v})=\begin{bmatrix}2 & 2 \\ 1 & -3\end{bmatrix}·\begin{bmatrix}-1 \\ 1\end{bmatrix}=\begin{bmatrix}0 \\ 4\end{bmatrix}$
$(L_{2}\odot L_{1})(\vec{v})=A^{\prime}·\vec{x}=(A_{2}·A_{1})\vec{x}$
$A^{\prime}=\begin{bmatrix}1 & -1 \\ 0 & -1\end{bmatrix}·\begin{bmatrix}2 & -4 \\ 1 & 2\end{bmatrix}=\begin{bmatrix}1 & -6 \\ -1 & -2\end{bmatrix}$

---

$L:\mathbb{R}^{2}\to \mathbb{R}^{3}$
def 1)
$L((x_{1},x_{2}))=(x_{1},x_{1}+x_{2},-x_{2})$
def 2)
$L((x_{1},x_{2}))=A·\begin{bmatrix}x_{1} \\ x_{2}\end{bmatrix}$
$A=\begin{bmatrix}1 & 0 \\ 1 & 1 \\ 0 & -1\end{bmatrix}$
def 3)
$L(\vec{e}_{1})=(1,1,0)$
$L(\vec{e}_{2})=(0,1,-1)$

--

$\vec{x}=(-3,2)$

$L(\vec{x})=L(-3,2)=(-3,-1,2)$

$L(\vec{x})=\begin{bmatrix}1 & 0 \\ 1 & 1 \\ 0 & -1\end{bmatrix}·\begin{bmatrix}-3 \\ 2\end{bmatrix}=\begin{bmatrix}-3 \\ -1 \\ -2\end{bmatrix}$

$\vec{x}=(-3,2)=(-3)·\vec{e}_{1}+2\vec{e}_{2}$
$L(\vec{x})=(-3)·L(\vec{e}_{1})+2·L(\vec{e}_{2})=(-3)·(1,1,0)+2(0,1,-1)=(-3,-1,-2)$
---

$L:\mathbb{R}^{2}\to \mathbb{R}^{2}$
$L((1,1))=(-3,-1)$
$L((-1,1))=(1,-1)$
Find the formula of transformation
$(1,1)=\vec{e}_{1}+\vec{e}_{2}$
$(-1,1)=-\vec{e}_{1}+\vec{e}_{2}$
$L((1,1))=L(\vec{e}_{1})+L(\vec{e}_{2})$
$L(-1,1)=-L(\vec{e}_{1})+L(\vec{e}_{2})$
{
$L(\vec{e}_{1})+L(\vec{e}_{2})=(3,-1)$
$-L(\vec{e}_{1})+L(\vec{e}_{2})=(1,-1)$
{
$2·L(\vec{e}_{2})=(4,-2)$
$L(\vec{e}_{2})=(2,-1)$

$L(\vec{e}_{1})=(3,-1)-L(\vec{e}_{2})=(3,-1)-(2,-1)=(1,0)$

$A=\begin{bmatrix}1 & 2 \\ 0 & -1\end{bmatrix}$

$A^{-1}=-\frac{1}{1}\begin{bmatrix}-1 & -2 \\ 0 & 1\end{bmatrix}=\begin{bmatrix}1 & 2 \\ 0 & -1\end{bmatrix}$

$L^{\prime}=L\odot L$
$L^{\prime}(\vec{x})=A^{\prime}·\vec{x}$
$A^{\prime}=A·A=\begin{bmatrix}1 & 2 \\ 0 & -1\end{bmatrix}^{2}=\begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}$

---

$L:\mathbb{R}\to \mathbb{R}^{3}$
$L(x)=(x,2x,3x)$
$A_{3\times_{1}}=\begin{bmatrix}1 \\ 2 \\ 3\end{bmatrix}$

---

$L:\mathbb{R}^{3}\to \mathbb{R}$
$L((x_{1},x_{2},x_{3}))=(x_{1}+x_{2}+x_{3})$
$A_{1\times_{3}}=\begin{bmatrix}1 & 1 & 1\end{bmatrix}$
