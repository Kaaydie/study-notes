## Incompletly specified functions
![[Pasted image 20251104084351.png]]
$$
\begin{align}
 & x_{2}x_{1}=01 \\
 & x_{2}x_{1}=10 - \text{(not posibble on physical ground)-don't care(d,x,-,}\phi) \text{we will use "-"} \\
 &  
\end{align}
$$---
$F=\Sigma[0,1,2,(6)]_{xyz}$
(6) is don't care
$F=\Sigma[000,001,010,(110)]_{xyz}$
$F=\Pi[3,4,5,7,(6)]_{xyz}$
---
$F^{(1)}=\Sigma(0,1,2)_{xyz}$
$F^{(0)}=\Pi(3,4,5,7)_{xyz}$
---
All these are equvilent

| \   | yz  |     |     |     |
| --- | --- | --- | --- | --- |
| x   | 00  | 01  | 11  | 10  |
| 0   | 1   | 1   | [[  | 1   |
| 1   | ((  |     | ]]  | -)) |
$F=(\bar{x})(\bar{y}+\bar{z})$

| \   | yz    |     |     |     |
| --- | ----- | --- | --- | --- |
| x   | 00    | 01  | 11  | 10  |
| 0   | ((1]] | 1)) | 0   | [[1 |
| 1   | 0     | 0   | 0   |     |
$F=\bar{x}\bar{y}+\bar{x}\bar{z}$

| \   | yz  |     |     |     |
| --- | --- | --- | --- | --- |
| x   | 00  | 01  | 11  | 10  |
| 0   | ((  | ))  | 0   | [[  |
| 1   | 0   | 0   | 0   | -]] |
$F=\bar{x}\bar{y}+y\bar{z}$

---
## Hazard in combinational circuits
img
<u>Recognition of hazard in Kmap</u>
![[Pasted image 20251104094209.png]]

| \   | bc  |     |         |         |
| --- | --- | --- | ------- | ------- |
| a   | 00  | 01  | 11      | 10      |
| 0   |     |     |         | ((1     |
| 1   |     | [[1 | {{1]]<- | ->1))}} |
                              ↑Hs1
$Z=ac+b\bar{c}+\underline{ab}$
		    ↑antihazard group

---
## Number systems (weighted positioned)
$(N)_{r}=\underline{d_{j-1}\dots d_{1}d_{0}}\cdot d_{-1}d_{-2}\dots d_{-k}$ d={0,...,r-1}
			I                K
			intiger      fraction

$(N)_{10}=\sum_{i=-k}^{i-1}=d_{i}r^{i}$

123
$1*16^{2}+2*16^{1}+3*16^{0}$
216+32+3=291
---
$$
\begin{align}
 & \text{Binary} & \text{Hexadecimal} \\
 & (N)_{2}=\sum^{i-1}_{i=-k}d_{i}2^{i}\leftrightarrow  & (N)_{16}=\sum^{i-1}_{i=-k}d_{i}16^{i}
\end{align}
$$