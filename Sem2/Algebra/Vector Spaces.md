$<.,.>: V \times V\to \mathbb{R}$
$<u,v>=<v,u>$
$<u+v,w> = <u,w>+<v,w>$
$<\alpha u,v> = \alpha ·<u,v>$
$<u,u> \geq \cap <u,u> = 0$
			$\iff u=0$

$||\vec{X}||=\sqrt{ <x,x> }$

$||\vec{X}||,d(\vec{x},\vec{y})=||\vec{x}-\vec{y}||$
---

# 1) $\vec{u},\vec{v}\epsilon \mathbb{R}^{2}$
$\vec{w}=(w_{1},w_{2})$
$\vec{u}=(u_{1},u_{2})$
$\vec{v}=(v_{1},v_{2})$

---

$<\vec{u},\vec{v}>=u_{1}·v_{1}+u_{2}·v_{2}$
$<\vec{u},\vec{u}>=u_{1}^{2}-u_{2}^{2}$
$\vec{x}=(1,2)$
$<\vec{x},\vec{x}\geq 1-4=-3$
NOT a vector space

---
# 2

$<\vec{u},\vec{v}>=2 \ ||\vec{u}||=1$
$<\vec{u},\vec{w}> =2 \ ||\vec{v}||=2$
$<\vec{v},\vec{w}> = -3 \ ||\vec{w}||=3$

$\vec{x}=2\vec{u}-w$
$\vec{y}=\vec{u}+\vec{v}$
$<\vec{x},\vec{y}>= <2\vec{u}+w,\vec{u}+\vec{v}>$=
=$<2\vec{u},\vec{u}+\vec{v}>+<(-1)\vec{w},\vec{u}+\vec{y}>$=
=$2<\vec{u},\vec{u}+\vec{v}>+ (-1)·<\vec{w},\vec{u}+\vec{v}>$=
=$2<\vec{u}+\vec{v},\vec{u}>+(-1)·<\vec{u}+\vec{v},\vec{w}>$=
=$2(<\underbrace{ \vec{u},\vec{u} }_{ ||\vec{u}||^{2}=1 }>+<\underbrace{ \vec{v},\vec{u} }_{ 2 }>)+(-1)·(<\underbrace{ \vec{u},\vec{w} }_{ 3 }>+<\underbrace{ \vec{v},\vec{w} }_{ -3 }>)=2·3=6$

---

$||\vec{u}+2\vec{v}||=\sqrt{ <u+2v,u+2v> }=\sqrt{ 25 }=5$
=$<u+2v,u+2v>$=
=$<u,u+2v>+<2v,u+2v>=$=
=$<u,u>+<u,2v>+<2v,u>+<2v,2v>$=
=$<\underbrace{ u,u }_{ 1 }>+2<\underbrace{ u,v }_{ 2 }>+2<\underbrace{ v,u }_{ 2 }>+4<\underbrace{ v,v }_{ 4 }>$

---

# 3

$\cos(\angle(\vec{u},\vec{v}))= \frac{<\vec{u},\vec{v}>}{||\vec{u}||·||\vec{v}||}$

$V=\mathbb{R}^{3}$
a) $<\vec{u},\vec{v}>=u_{1}v_{1}+u_{2}v_{2}+u_{3}v_{3}$
b) $<\vec{u},\vec{v}>=u_{1}v_{1}+2u_{2}v_{2}+3u_{3}v_{3}$

$\vec{x}=(1,-1,1)$
$\vec{y}=(2,-2,-2)$
$\alpha=\angle(\vec{x},\vec{y})$

a) 
$<\vec{x},\vec{y}> = 2+2-2=2$
$||\vec{x}||=\sqrt{ 1+1+1 }=\sqrt{ 3 }$
$||\vec{y}||=\sqrt{ 4+4+4 }=\sqrt{ 12 }=2 \sqrt{ 3 }$

$\cos(\angle(\vec{x},\vec{y}))=\frac{2}{6}=\frac{1}{3}$

b)
$<\vec{x},\vec{y}>= 2+2·2+3·(-2)=0\implies \angle(\vec{x},\vec{y})=\frac{\pi}{2}$
$\vec{x} _|_ \vec{y}$
$<\vec{x},\vec{y}> =0!$

---

# 4
build all possible pairs
check if ortognal
$S_{1}=\{ (2,-7,1),(-6,-3,9),(3,1,-1) \}$


---

# 5

$B_{1}((2,-3,1),(4,1,4),(0,1,0))$
$\vec{v_{1}},\vec{v_{2}},\vec{v_{3}}$
$B_{2}=\left( \left( \frac{2}{3},-\frac{2}{3}, \frac{1}{3} \right),\left( \frac{2}{3}, \frac{1}{3} , -\frac{2}{3} \right),\left( \frac{1}{3}, \frac{2}{3}, \frac{2}{3} \right) \right)$
$\vec{u_{1}},\vec{u_{2}},\vec{u_{3}}$

$\vec{x}=(6,-1,2)$

$(\vec{x})_{B_{1}}=\begin{bmatrix}\alpha  \\ \beta \\ \gamma\end{bmatrix}$
$\alpha·\vec{v_{1}}+\beta·\vec{v_{2}}+\gamma·\vec{v_{3}}=\vec{x}$
$\begin{bmatrix}2 & 4 & 0 & | & 6 \\ -3 & 1 & 1 & | & -1 \\ 1 & 1 & 0 & | & 2\end{bmatrix}\to$


$(\vec{x})_{B_{2}}=\begin{bmatrix}<\vec{x},\vec{u_{1}}> \\ <\vec{x},\vec{u_{2}}> \\ <\vec{x},\vec{u_{3}}>\end{bmatrix}$=$\begin{bmatrix} \frac{16}{3} \\ \frac{7}{3} \\ \frac{8}{3} \end{bmatrix}$
only possible if base is ortonormal

# 6 how to turn space into ortonormal

$B=((1,1,1),(-1,1,0),(1,2,1))$
$\vec{v_{1}},\vec{v_{2}},\vec{v_{3}}$

$B^{\prime}=(\vec{w_{1}},\vec{w_{2}},\vec{w_{3}})$ ortogonal
$||w_{1}||=\sqrt{ 3 }$
$||w_{2}||=\sqrt{ 2 }$
$||w_{3}||=\sqrt{ 6 }$

$\vec{w_{1}}=\vec{v_{1}}=(1,1,1)$

$\vec{w_{2}}=\vec{v_{2}}- \frac{<\vec{w_{1}},\vec{v_{2}}>}{||\vec{w_{1}}||^{2}}·\vec{w_{1}}=(-1,1,0)- \frac{(-1)+1+0}{3}·(1,1,1)=(-1,1,0)$
$\vec{w_{3}}=\vec{v_{3}}- \frac{<\vec{w_{1}},\vec{v_{3}}>}{||\vec{w_{1}}||^{2}}·\vec{w_{1}}- \frac{<\vec{w_{2}},\vec{v_{3}}>}{||\vec{w_{2}}||^{2}}$=
=$(1,2,1)-\frac{4}{3}(1,1,1)-\frac{1}{2}(-1,1,0)$=
=$(1,2,1)-\left( \frac{4}{3 }, \frac{4}{3}, \frac{4}{3} \right)-\left( -\frac{1}{2 }, \frac{1}{2},0 \right)=\left( \frac{1}{6}, \frac{1}{6}, -\frac{1}{3} \right)$

-

$B^{\prime\prime}=(\vec{u_{1}},\vec{u_{2}},\vec{u_{3}})$=$\left( \left( \frac{1}{\sqrt{ 3 }}, \right) \right)$
$\vec{u_{i}}= \frac{\vec{w_{i}}}{||\vec{w_{i}}||}$

The following example for test
$V=\mathbb{R}^{4}$
$W=\{(x,y,x+y,x-y):x,y\epsilon \mathbb{R} \}$

prove that w is subspace of v,
find the basis of w
find the space and dimmesions of w,
find the ortonormal basis of w
