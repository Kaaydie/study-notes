eigen value
$\det(A-\lambda I)$
eigen vector
$(A-\lambda I)\vec{x}=0$
$D=P^{-1}·A·P$
# ex 1
$A=\begin{bmatrix}10 & -9 \\  4 & -2\end{bmatrix}$

characteristic polynomial

$@\varphi(\lambda)=\det \begin{bmatrix}10-\lambda & -9 \\  4 & -2-\lambda\end{bmatrix}$
=$(10-\lambda)(-2-\lambda)+36$
=$-20-10\lambda+2\lambda+\lambda^{2}+36$
=$\lambda^{2}-8\lambda+16=(\lambda-4)^{2}=0$

$\lambda=4 (a.m=2)$
$(A-\lambda I)\vec{x}=0$
$(A-4I)\vec{x}=0$
$A-4I=\begin{bmatrix}6 & 9 \\  4 & -6\end{bmatrix}\begin{matrix}:6 \\  :4\end{matrix}$~$\begin{bmatrix}1 & -\frac{3}{2} \\  1 & -\frac{3}{2}\end{bmatrix}$
    $x_{1}x_{2}$
~$\begin{bmatrix}1 & -\frac{3}{2} \\  0 & 0\end{bmatrix}$=
       ↓
       t
$$
\begin{cases}
x_{1}=\frac{3}{2}t \\
x_{2}=t
\end{cases},t\in \mathbb{C}\set{0}
$$
$\vec{x}=\begin{bmatrix}3 \\  2\end{bmatrix}$

---
# ex 2

$A=\begin{bmatrix}1 & 2 & 0 \\  2 & 2 & 0 \\  0 & 0 & 3\end{bmatrix}$
$\varphi(\lambda)=\det \begin{bmatrix}1-\lambda & 2 & 0 \\  2 & 2-\lambda & 0 \\  0 & 0 & 3-\lambda\end{bmatrix}$
=$\det \begin{bmatrix}1-\lambda & 2 \\  2 & 2-\lambda\end{bmatrix}·\det \begin{bmatrix}3 & -\lambda\end{bmatrix}$
=$(\lambda^{2}-3\lambda-2)(3-\lambda)$
$\Delta=9+8=17$
$\lambda_{1}=\frac{3+\sqrt{ 17 }}{2}$
$\lambda_{2}=\frac{3-\sqrt{ 17 }}{2}$
$\lambda_{3}=3$

Matrix A is diagnoizable

# ex3
$A=\begin{bmatrix}-7 & 0 & -3 \\  -2 & 1 & -1 \\  18 & 0 & 8\end{bmatrix}$
$\varphi(\lambda)=\det \begin{bmatrix}-7-\lambda & 0 & -3 \\  -2 & 1-\lambda & -1 \\  18 & 0 & 8-\lambda\end{bmatrix}$
$(1-\lambda)(\lambda-2)(\lambda+1)=0$
$\lambda_{1}=1,\lambda_{2}=2,\lambda_{3}=-1$

$(A-I)=\begin{bmatrix}-8 & 0 & -3 \\  -2 & 0 & -1 \\  18 & 0 & 7\end{bmatrix}$~$\begin{bmatrix}1 & 0 & \frac{1}{2} \\  -8 & 0 & -3 \\  18 & 0 & 7\end{bmatrix}$~$\begin{bmatrix}1 & 0 & \frac{1}{2} \\  0 & 0 & 1 \\  0 & 0 & -2\end{bmatrix}$~$\begin{bmatrix}1 & 0 & 0 \\  0 & 0 & 1 \\  0 & 0 & 0\end{bmatrix}$
$x_{1}=0$
$x_{2}=t$
$x_{3}=0$
$t\neq 0$
$x_{1}=\begin{bmatrix}0 & \\  1 \\  0\end{bmatrix}$
