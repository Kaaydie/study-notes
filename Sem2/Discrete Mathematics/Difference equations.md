generating function method
a) $g_{n+1}=g_{n}+2^{n+1},g_{0}=-1$

$G(s)=g_{0}+g_{1}s+g_{2}s^{2}+\dots$
1) Transform the difference equasion to generating function ( gf )
$g_{n+1}=g_{n}+2^{n+1}$
$g_{n+1}=g_{n}+2·2^{n}$ ->$\boxed{a^{n}\to G(a^{n})=\frac{1}{1-as}}$
↓                         ↓
$\frac{1}{s}[G(s)-g_{0}]=G(s)+2· \frac{1}{1-2s}$
2) extract GTs
$\frac{1}{s}[G(s)+1]=G(s)+\frac{2}{1-2s}$ /·s
$G(s)+1=s·G(s)+\frac{2s}{1-2s}$
$G(s)(1-s)=\frac{2s}{1-2s}-1=\frac{4s-1}{1-2s}$
$G(s)=\frac{4s-1}{(1-2s)(1-s)}$ (\*)<- rational function ~> partial fractions

$\frac{4s-1}{(1-2s)(1-s)}=\frac{A}{1-2s}+\frac{B}{1-s}$
$4s-1=A(1-s)+B(1-2s)$

$[s^{1}]:4=-A-2B$
$[s^{0}]:-1=A+B$
$3=-B$
$A=-1-B=-1+3=2$

(\*)
$\underbrace{ G(s) }_{ g_{n} }=\frac{2}{1-2s}-\frac{3}{1-s}=2·\underbrace{ \frac{1}{1-2s} }_{ 2·2^{n} }-3·\underbrace{ \frac{1}{1-s} }_{ -3·\mathbb{1}(n) }$
↓
3) return to original domain
$g_{n}=2^{n+1}-3$

---

Z-transform method
b) $f_{n+1}-f_{n}=(-2)^{n},f_{0}=1$

1) Transform difference equasion to gf
$Z[f_{n+1}-f_{n}]=Z[(-2)^{n}]$
$Z[f_{n+1}]-Z[f_{n}]=\frac{Z}{Z+2}$

$\boxed{Z[a^{n}]=\frac{Z}{Z-a}}$

$Z[\varphi(Z)-f_{0}]-\varphi(Z)=\frac{Z}{Z+2}$

2) .
$Z[\varphi(Z)-1]-\varphi(Z)=\frac{Z}{Z+2}$
$Z\varphi(Z)-\varphi(Z)=\frac{Z}{Z+2}+Z$
$(Z-1)\varphi(Z)=\frac{Z+Z(Z+2)}{Z+2}$
$\varphi(Z)=\frac{Z(1+Z+2)}{(Z+2)(Z-1)}=\frac{Z(Z+3)}{(Z+2)(Z-1)}$
$\frac{\varphi(Z)}{Z}=\frac{Z+3}{(Z+3)(Z-1)}$<- proper rational function

$\frac{Z+3}{(Z+2)(Z-1)}=\frac{A}{Z+2}+\frac{B}{Z-1}$

$Z^{1}:1=A+B$
$Z^{0}:3=-A+2B$

$\varphi(Z)=-\frac{1}{3}·\underbrace{ \frac{Z}{Z+2} }_{ (-2)^{n} }+\frac{4}{3}·\underbrace{ \frac{Z}{Z-1} }_{ \mathbb{1}(n) }$
---

# 2g) second order

$s_{0}=1,s_{1}=2,s_{n}=s_{n-2}-s_{n-1},n\geq_{2}$
			 $s_{n}-s_{n-2}+s_{n-1}=0$
hom LDE 2nd order
$r^{2}-1+r=0$
$r^{2}+r-1=0$
$\Delta=1+4·1·1=5$
$r_{1}=\frac{-1-\sqrt{ 5 }}{2},r_{2}=\frac{-1+\sqrt{ 5 }}{2}$

$S_{n}=C_{1}·\left( \frac{-1-\sqrt{ 5 }}{2} \right)^{n}+C_{2}·\left( \frac{-1+\sqrt{ 5 }}{2} \right)^{n}$
use intial concdition to get $C_{1},C_{2}$

$1=S_{n}=C_{1}·\left( \frac{-1-\sqrt{ 5 }}{2} \right)^{0}+C_{2}·\left( \frac{-1+\sqrt{ 5 }}{2} \right)^{0}$
$2=S_{n}=C_{1}·\left( \frac{-1-\sqrt{ 5 }}{2} \right)^{1}+C_{2}·\left( \frac{-1+\sqrt{ 5 }}{2} \right)^{1}$
$C_{1}=1-C_{2}$
$2=(1-C_{2})·\left( \frac{-1-\sqrt{ 5 }}{2} \right)+C_{2}\left( \frac{-1+\sqrt{ 5 }}{2} \right)$ /·2
$4=(2-2C_{2})·(-1-\sqrt{ 5 })+2C_{2}·(-1+\sqrt{ 5 })$
$4=-2-2\sqrt{ 5 }+2C_{2}+2\sqrt{ 5 }C_{2}-2C_{2}+2\sqrt{ 5 }C_{2}$
$6+2\sqrt{ 5 }=4\sqrt{ 5 }C_{2}$
$C_{2}=\frac{6+2\sqrt{ 5 }}{4\sqrt{ 5 }}$
$C_{1}=\frac{4\sqrt{ 5 }-6-2\sqrt{ 5 }}{4\sqrt{ 5 }}=\frac{2\sqrt{ 5 }-6}{4\sqrt{ 5 }}=\frac{2(\sqrt{ 5 }·3)}{4\sqrt{ 5 }}=\frac{\sqrt{ 5 }-3}{2\sqrt{ 5 }}$

$S_{n}=\frac{\sqrt{ 5-3 }}{2\sqrt{ 5 }}·\left( \frac{-1-\sqrt{ 5 }}{2} \right)^{n}+\frac{6+2\sqrt{ 5 }}{4\sqrt{ 5 }}·\left( \frac{-1+\sqrt{ 5 }}{2} \right)^{n}$

# 3a)
$S_{0}=2,S_{1}=1,S_{2}=3$
$S_{n}=2s_{n-1}+s_{n-2}-2s_{n+3},n\geq 3$
$S_{n}-2s_{n-1}-s_{n-2}+2_{s-3}=0$
$s_{n}=r^{n},(r\neq_{0})$
$r^{n}-2r^{n-1}-r^{n-2}+2r^{n-3}=0 /·r^{n-3}$
$r^{3}-2r^{2}-r+2=0$
characterictic equasion
roots:
$r^{2}(r-2)-(r-2)=0$
$(r-2)(r^{2}-1)=0$
$(r-2)(r+1)(r-1)=0$
$r_{0}=2,r_{1}=-1,r_{2}=1$

$S_{n}=C_{1}·2^{n}+C_{2}·(-1)^{n}+C_{3}·1^{n}$
{
$2=C_{1}+C_{2}+C_{3}$
$1=C_{1}·2+C_{2}·(-1)+C_{3}·1$
$3=C_{1}·4+C_{2}·(-1)+C_{3}·1$
{

{
$2=C_{1}+C_{2}+C_{3}$
$1=2C_{1}-C_{2}+C_{3}$
$3=4C_{1}+C_{2}+C_{3}$
{

$1=3C_{1}\implies C_{1}=\frac{1}{3}$
$3=3C_{1}+2C_{2}\implies C_{2}=\left( 3-3·\frac{1}{3} \right)·\frac{1}{2}=1$
$C_{3}=2-C_{1}-C_{2}=2-\frac{1}{3}-1=\frac{2}{3}$

Solution
$\boxed{s_{n}=\frac{1}{3}·2^{n}+(-1)^{n}+\frac{1}{3}}$

---

# 4c) non homogenous case

$s_{0}=-1,s_{1}=2,s_{n}=3s_{n-1}+4s_{n-2}+n^{2}$
$s_{n}=3s_{n-1}-4s_{n-2}=n^{2}\neq 0$
I HLDE
$s_{n}-3s_{n-1}-4s_{n-2}=0$
$r^{2}-3r-4=0$
$\Delta=9+4·4=25$
$r_{1}=\frac{3-5}{2}=-1$
$r_{2}=\frac{3+5}{2}=4$
$s_{n}=C_{1}·(-1)^{n}+C_{2}·4^{n}$

II NLDE
we guess solutions of the form of g, have it is quadratic polynomial
so we asume 
$\bar{s_{n}}=an^{2}+bn+c$
$\bar{s_{n-1}}=a(n-1)^{2}+b(n-1)+c$
$\bar{s_{n-2}}=a(n-2)^{2}+b(n-2)+c$
$an^{2}+bn+c-3(a(n^{2}-2n+1)+bn-b+c)-4(a(n^{2}-4n+4)+bn-2b+c)=n^{2}$
$an^{2}+bn+c-3an^{2}+6an-3a-3bn+3b-3c-4an^{2}+16an-16a-4ba+8b-4c=n^{2}$
$-6an^{2}+(-6b+22a)n+(-6c-19a+11b)=n^{2}$
{
$-6a=1$
$-6b+22a=0$
$-6c-19a+11b=0$
{
$a=-\frac{1}{3}$
$b=-\frac{11}{18}$
$c=\frac{32}{9}$

so particular soludion of NLDE is
$\overline{ s_{n} }=-\frac{1}{6}n^{2}-\frac{11}{18}n+\frac{32}{9}$

III. $s_{n}=C_{1}·(-1)^{n}+C_{2}·4^{n}-\frac{1}{6}n^{2}-\frac{11}{18}n+\frac{32}{9}$
-> apply initial conditions to get C
{
$-1=C_{1}+C_{2}+\frac{32}{9}$
$2=-C_{1}+4C_{2}-\frac{1}{6}-\frac{11}{18}+\frac{32}{9}$
{

$1=5C_{2}+\frac{64}{9}-\frac{14}{18}=5C_{2}+\frac{64}{9}-\frac{7}{9}=5C_{2}+\frac{57}{9}=5C_{2}+\frac{19}{3}$
$C_{2}=-\frac{16}{3·5}=-\frac{16}{15}$
$C_{1}=-1-C_{2}-\frac{32}{9}=-\frac{41}{9}+\frac{16}{15}=\frac{-2·5}{45}+\frac{48}{45}=-\frac{157}{45}$

Answer:
$S_{n}=-\frac{157}{45}·(-1)^{n}-\frac{16}{15}·4^{n}-\frac{1}{6}n^{2}-\frac{11}{18}n+\frac{32}{9}$

---

# 6a)
$f_{0}=2$
$\underbrace{ \Delta f_{n} }_{ f_{n+1}-f_{n} }=3f_{n}+1$
delta means the increment betwen 2 terms
