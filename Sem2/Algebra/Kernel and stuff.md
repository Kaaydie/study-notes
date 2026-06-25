# ex1
$T:\mathbb{R}^{2}\to \mathbb{R}^{3}$
$T((x_{1},x_{2}))=(x_{1}+x_{2},x_{1}-x_{2},x_{2}-x_{1})$
$A=\begin{bmatrix}1 & 1 \\  1 & -1 \\  -1 & 1\end{bmatrix}$
$ker(T)=?$
$range(T)=?$

$\vec{x}\in ker(T)\iff T(x)=\vec{0}$
		$A\vec{x}=\vec{0}$
   $x_{1}$      $x_{2}$
$\begin{bmatrix}1 & 1 & | & 0 \\  1 & -1 & | & 0 \\  -1 & 1 & | & 0\end{bmatrix}\begin{matrix}    \\   +r_{1}·(-1) \\  +r_{1}·1\end{matrix}$ ~
$\begin{bmatrix}1 & 1 \\  0 & -2 \\  \end{bmatrix}$~$\begin{bmatrix}1 & 1 \\  0 & 1 \\  0 & 2\end{bmatrix}$
~$\begin{bmatrix}1 & 0 & | & 0 \\  0 & 1 & | & 0 \\  0 & 0 & | & 0\end{bmatrix}$
$ker(T)=\{ \begin{bmatrix}0 \\  0\end{bmatrix} \}$
$nullity(T)=0$
$rank(T)=2$
$Range(T)=\{ t\begin{bmatrix}1 \\  1 \\  -1\end{bmatrix}+s\begin{bmatrix}1 \\  -1 \\  1\end{bmatrix},t,s\in \mathbb{R} \}$
---
# ex 2
$T:\mathbb{R}^{3}\to \mathbb{R}^{3}$
$T((x_{1},x_{2},x_{3}))=(x_{1}+2x_{2},3x_{1}+x_{3},0)$
$A=\begin{bmatrix}1 & 2 & 0 \\  3 & 0 & 1 \\  0 & 0 & 0\end{bmatrix}$
$A\vec{x}=\vec{0}\iff \vec{x}\in ker(t)$
$x_{1} \ x_{2} \ x_{3}$
$\begin{bmatrix}1 & 2 & 0 & | & 0 \\  3 & 0 & 1 & | & 0 \\  0 & 0 & 0 & | & 0\end{bmatrix}+r_{1}·(-3)$

$\begin{bmatrix}1 & 2 & 0 \\  0 & -6 & 1 \\  0 & 0 & 0\end{bmatrix}$
$x_{1} \ x_{3} \ x_{2}$
$\begin{bmatrix}① & 0 & 2 \\  0 & ① & 6 \\  0 & 0 & \underbrace{ 0 }_{ t }\end{bmatrix}$

$x_{1}=-2t$
$x_{2}=t$
$x_{3}=6t$
$t\in \mathbb{R}$

$nullity(T)=1$
$rank(T)=2$
$kerT=\{ t\begin{bmatrix}-2 \\  1 \\  6\end{bmatrix},t\in \mathbb{R} \}$
$range(T)=\{  \}$

$Ex 3$
$T:\mathbb{R}^{3}\to \mathbb{R}^{3}$
$T((x_{1},x_{2},x_{3}))=(x_{1}+x_{2},x_{2}+x_{3},x_{1}+x_{3})$
$A=\begin{bmatrix}1 & 1 & 0 \\  0 & 1 & 1 \\  1 & 0 & 1\end{bmatrix}$
$A\vec{x}=\vec{0}\iff \vec{x}\in ker(t)$

$x_{1} \ x_{2} \ x_{3}$
$\begin{bmatrix}① & 1 & 0 \\  0 & 1 & 1 \\  1 & 0 & 1\end{bmatrix}\begin{matrix} \\   \\  +r_{1}·(-1)\end{matrix}$~$\begin{bmatrix}1 & 1 & 0 \\  0 & ① & 1 \\  0 & -1 & 1\end{bmatrix}\begin{matrix}+r_{2}·(-1) \\   \\  +r_{2}·1\end{matrix}$

~$\begin{bmatrix}1 & 0 & -1 \\  0 & 1 & 1 \\  0 & 0 & 2\end{bmatrix}\begin{matrix} \\   \\  :2\end{matrix}$~$\begin{bmatrix}1 & 0 & -1 \\  0 & 1 & 1 \\  0 & 0 & 1\end{bmatrix}\begin{matrix}+r_{3} \\  +r_{3}·(-1) \\   \\  \end{matrix}$~$\begin{bmatrix}1 & 0 & 0 & | & 0 \\  0 & 1 & 0 & | & 0 \\  0 & 0 & 1 & | & 0\end{bmatrix}$

$ker(T)=\{ \begin{bmatrix}0 \\  0 \\  0\end{bmatrix} \}=\{ \vec{0} \}$
$nullity(T)=0\implies rank(T)=3\implies range(T)=\mathbb{R}^{3}$
