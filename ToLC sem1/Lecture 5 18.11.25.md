$(x)_{r}$
r-th complement of X -> $\bar{\bar{x}}=r^{j}-x$ fv $x\neq_{0}, \ \bar{\bar{x}}=0 \ for \ x=0$ 
(r-1)-st complement of x -> $\bar{x}=r^{j}-x-r^{-k}$
$r=z \to BIN$
$2^{nd}$ complement of x -> $\bar{\bar{x}}=\bar{x}+\text{least significant bit}$
$1^{st}\text{ complement of }x\to \bar{x}\text{ is created by negation (logical complement)of set bits}$
Example
$x=1001$
$\bar{x}=0110$
      +1
$\bar{\bar{x}}=\overline{ 0111 }$

---

# Negative numbers in BINary system

$[]$$[\text{value of x}]$
↑
signed bit of x
0 -> +
1 -> -
Negative numbers we have 3 represenations:
1) Sign-absolute value
2) sign-$1^{st}$ complement
3) sign-$2^{nd}$ complement

Example:
4bits,
$+3\ 0011$
$-3\ 1011$

"Why on earth or on hell if you wish"
+0 -0 0000 1000
+0 -0 0000 1111
+0 -0 0000 0000

---

# Codes
systems of symbols representing some objects/situations
Binary codes -> symbols are represented by sequences of bits

## Decimal-binary codes (used for representation of decimal digits by sequence of bits)

Nature Binary code(BCD)
self complementary:
Aiken's Exess-3

|     | $2^{3}2^{2}2^{1}2^{0}$ | $2^{1}2^{2}2^{1}2^{0}$ | x+3                    |                                                      |
| --- | ---------------------- | ---------------------- | ---------------------- | ---------------------------------------------------- |
|     | BCD                    | Aiken's                | Exess-3                | 1-out-of-10                                          |
|     | $x_{3}x_{2}x_{1}x_{0}$ | $x_{3}x_{2}x_{1}x_{0}$ | $x_{3}x_{2}x_{1}x_{0}$ | $x_{9}x_{8}x_{7}x_{6}x_{5}x_{4}x_{3}x_{2}x_{1}x_{0}$ |
| 0   | 0000                   | 0000                   | 0011                   | 0000000001                                           |
| 1   | 0001                   | 0001                   | 0100                   | 0000000010                                           |
| 2   | 0010                   | 0010                   | 0101                   | 0000000100                                           |
| 3   | 0011                   | 0011                   | 0110                   | 0000001000                                           |
| 4   | 0100                   | <u>0100</u>            | <u>0111</u>            | 0000010000                                           |
| 5   | 0101                   | 1011                   | 1000                   | 0000100000                                           |
| 6   | 0110                   | 1100                   | 1001                   | 0001000000                                           |
| 7   | 0111                   | 1101                   | 1010                   | 0010000000                                           |
| 8   | 1000                   | 1110                   | 1011                   | 0100000000                                           |
| 9   | 1001                   | 1111                   | 1100                   | 1000000000                                           |
|     |                        |                        |                        |                                                      |
Code converion
Encoder: which convert 1-out-of-10 to any code
Decoders: which convert any code to 1-out-of-10
Translators: which convert any code to some other code
			(none of them is 1-out-of-10)

## Cyclic codes
Grey's code

|     |     | Grey's                 | custom |
| --- | --- | ---------------------- | ------ |
|     |     | $x_{3}x_{2}x_{1}x_{0}$ |        |
|     | 0   | 0000                   | 0101   |
|     | 1   | 000==1==               | 0111   |
|     | 2   | 0011                   | 0110   |
|     | 3   | 00==10==               | 0010   |
|     | 4   | 0110                   | 0011   |
|     | 5   | 0111                   | 0001   |
|     | 6   | 0101                   | 0000   |
|     | 7   | 0==100==               | 0100   |
|     | 8   | 1100                   | 1100   |
|     | 9   | 1101                   | 1000   |
|     | a   | 1111                   | 1001   |
|     | b   | 1110                   | 1011   |
|     | c   | 1110                   | 1010   |
|     | d   | 1011                   | 1110   |
|     | e   | 1001                   | 1111   |
|     | f   | 1000                   | 1101   |
Other cyclic codes
you can make custom cyclic codes as long as first and last are logical neighbors in k-maps

| \            | $x_{1}x_{0}$ |     |     |     |
| ------------ | ------------ | --- | --- | --- |
| $x_{3}x_{2}$ | 00           | 01  | 11  | 10  |
| 00           | 6            | 5   | 4   | 3   |
| 01           | 7            | 0   | 1   | 2   |
| 11           | 8            | f   | e   | d   |
| 10           | 9            | a   | b   | c   |
↑
Completly specified code

other2

| \            | $x_{1}x_{0}$ |     |     |     |
| ------------ | ------------ | --- | --- | --- |
| $x_{3}x_{2}$ | 00           | 01  | 11  | 10  |
| 00           | 0→           | 1→  | 2→  | 3↓  |
| 01           |              |     |     | 4↓  |
| 11           |              |     |     | 5↓  |
| 10           | 9←           | 8←  | 7←  | 6←  |
↑
example of incompleatly specified code

|     | $x_{3}x_{2}x_{1}x_{0}$ |
| --- | ---------------------- |
| 0   | 0000                   |
| 1   | 0001                   |
| 2   | 0011                   |
| 3   | 0010                   |
| 4   | 0110                   |
| 5   | 1110                   |
| 6   | 1010                   |
| 7   | 1011                   |
| 8   | 1001                   |
| 9   | 1000                   |
