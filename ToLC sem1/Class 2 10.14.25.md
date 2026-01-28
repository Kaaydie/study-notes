
## Algebraic minimization
###### ex1
$F=\bar{a}\bar{b}\bar{c}+bc+b \bar{c} =  /\text{T7a}$
$\bar{a}\bar{b}\bar{c} + b = / \text{T9a}$
$\bar{a}\bar{c}+b$

---
###### ex2
$F = x_{1}\bar{x}_{3}+\bar{x}_{1}x_{3}+\bar{x}_{1}x_{2}\bar{x_{3}} =$
$=x_{1}(x_{2}\bar{x_{2}})\bar{x_{3}} + \bar{x_{1}}\bar{x_{2}}x_{3} + \bar{x_{1}(x_{2}\bar{x_{2}})x_{3}+\bar{x_{1}x_{2}\bar{x_{3}}}}=$
$=x_{1}x_{2}\bar{x_{3}} + x_{1} \bar{x_{2} }\bar{x_{3}} +x_{1}\bar{x_{2}}\bar{x_{3}}+\bar{x_{1}}x_{2}x_{3}+\bar{x_{1}}\bar{x_{2}}x_{3} + \bar{x_{1}}x_{2}\bar{x_{3}}=$

$F=\Sigma (110,100,101,011,001,010)_{x_{1}x_{2}x_{3}}$
$F =\Sigma (6,4,5,3,1,2)_{x_{1}x_{2}x_{3}}$

$=x_{2}\bar{x_{3}}+x_{1}\bar{x_{2}}+\bar{x_{1}}x_{3}$

---
## Functional completnes
AND, OR, NOT = basic functionally completnes

OR, NOT $x*y=\bar{\bar{xy}}= \bar{\bar{x}\bar{y}}$

AND, NOT $x+y = \bar{\bar{(x+y)}}=\bar{\bar{x}\bar{y}}$

NAND

by only using either only (NAND  or NOR)  you can recreate every function

$F(x_{1},\dots,x_{n}) _{=}^{\text{T10b}} [F(1,\dots,x_{n})+\bar{x_{1}}] × [F(0,\dots,x_{n})+x_{1}]=$
$= [F(1,\dots,1)+(\bar{x_{1}}+\dots+\bar{x_{n}})]$ ×$[F(1,\dots,0)+(\bar{x_{1}}+\dots+x_{n})]$× $[F(0,\dots,]$
