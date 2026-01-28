Minimize $F=\sum(0,1,3,4,5,8,10,12)_{abcd}$
and implement with 
a) NANDs only
b) NORs only
$F=\sum(0000,0001,0011,0100,0101,1000,1010,1100)_{abcd}$

| \   | cd  |     |     |     |     |
| --- | --- | --- | --- | --- | --- |
| ab  | 00  | 01  | 11  | 10  |     |
| 00  | 1   | 1   | 1   |     | 0   |
| 01  | 1   | 1   |     |     | 4   |
| 11  | 1   |     |     |     | 12  |
| 10  | 1   |     |     | 1   | 8   |
|     | 0   | 1   | 3   | 2   |     |
![[Pasted image 20251104143305.png]]
$F=\bar{c}\bar{d}+\bar{a}\bar{c}+\bar{a}\bar{b}d+a\bar{b}\bar{d} \ \ \ \text{/demorgan theorem}$
$F=\overline{\overline{\bar{c}\bar{d}+\bar{a}\bar{c}+\bar{a}\bar{b}d+a\bar{b}\bar{d}}}=$
$=\overline{\bar{c}\bar{d}}\cdot \overline{\bar{a}\bar{c}}\cdot \overline{\bar{a}\bar{b}d}\cdot \overline{a\bar{b}\bar{d}}$
$F=\bar{c}\bar{d}+\bar{a}\bar{c}+\bar{a}\bar{b}d+a\bar{b}\bar{d}$
$F=\overline{\overline{\bar{c}\bar{d}}}+\overline{\overline{\bar{a}\bar{c}}}+\overline{\overline{\bar{a}\bar{b}d}}+\overline{\overline{a\bar{b}}\bar{d}}$
$= \overline{\overline{\overline{c+d}+\overline{a+c}+}}$
$= \overline{\overline{\overline{c+d}+\overline{a+c}+\overline{a+b+\bar{d}}+\overline{\bar{a}+b+d}}}$


---


| \   | cd  |     |     |     |
| --- | --- | --- | --- | --- |
| ab  | 00  | 01  | 11  | 10  |
| 00  |     |     |     | 0   |
| 01  |     |     | 0   | 0   |
| 11  |     | 0   | 0   | 0   |
| 10  |     | 0   | 0   |     |
$F=(\bar{a}+\bar{d})·(\bar{b}+\bar{c})·(a+\bar{c}+d)$
$F=¬¬(\bar{a}+\bar{d})·¬¬(\bar{b}+\bar{c})·¬¬(a+\bar{c}+d)=$
$=\overline{\overline{\overline{a·d}·\overline{b·c}·\overline{\bar{a}·c·\bar{d}}}}$
![[Pasted image 20251104145316.png]]

---
$F=\overline{\overline{(¬a+¬b)(¬b+¬c)(a+¬c+d)}}$
$=\overline{\overline{\bar{a}+\bar{d}}+\overline{\bar{b}+bar}+\overline{\bar{b}+\bar{c}+d}}$
![[Pasted image 20251104145950.png]]

---
## Translate to HEX
(N)$_{2}$ 10101110011.1011111

0101_0111_0011_.1011_1110
5_7_3.B_E
$5·16^{2}+7·16^{1}+3·16^{0}.11·16^{-1}+14·16^{-2}$
1395.7421875

---
# Negative numbers
## minimize F.Z given by
$$
\begin{align}
\begin{cases}
Z^{(1)}=\sum(1,3,4,11,16,24,26,31)_{x_{4}x_{3}x_{2}x_{1}x_{0}} \\
Z^{(0)}=\Pi(5,7,25,30)_{x_{4}x_{3}x_{2}x_{1}x_{0}}
\end{cases}
\end{align}
$$

| \            | $x_{2}x_{1}x_{0}$ |     |     |     | \|  |     |     |     |     |     |
| ------------ | ----------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| $x_{4}x_{3}$ | 000               | 001 | 011 | 010 | \|  | 110 | 111 | 101 | 100 |     |
| 00           |                   | 1   | 1   |     | \|  | {   | _0  | _0  | 1   | 0   |
| 01           |                   |     | 1   |     | \|  |     | __  | __  |     | 8   |
| 11           | 1                 | -0  | -   | 1   | \|  |     | 1   |     |     | 24  |
| 10           | 1                 | -   | -   |     | \|  | 0}  |     |     |     | 16  |
|              | 0                 | 1   | 3   | 2   | \|  | 6   | 7   | 5   | 4   |     |
F
Hazards betwen at least 1 don't care are illeverant
$Z=(¬x_{1}+x_{2}+¬x_{0})(¬x_{2}+¬x_{1}+x_{0})(x_{4}+¬x_{1}+x_{0})$
$Z=\overline{\overline{(¬x_{1}+x_{2}+¬x_{0})(¬x_{2}+¬x_{1}+x_{0})(x_{4}+¬x_{1}+x_{0})}}$
$=\overline{¬x_{4}+x_{2}+¬x_{0}}+\overline{¬x_{2}+¬x_{1}+x_{0}}+\overline{x_{4}+¬x_{2}+¬x0}$

Homework:
do this a SOP