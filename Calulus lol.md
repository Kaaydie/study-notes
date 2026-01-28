# Problem list 4
## 1. Calculate $\lim_{ n \to \infty }a_{n},$where

### 1.
$$
\begin{align}
 & a_{n}=\frac{n^{3}-2n^{2}+n+5}{2n^{2}-3n+1}  \\
 & a_{n}=\frac{\cancel{ n^{2} }\left( \overbrace{ n }^{ \infty }-\overbrace{ 2 }^{ 2 }+\overbrace{ \frac{1}{n} }^{ 0 }+\overbrace{ \frac{5}{n^{2}} }^{ 0 } \right)}{\cancel{ n^{2} }\left( \underbrace{ 2 }_{ 2 }-\underbrace{ \frac{3}{n} }_{ 0 }+\underbrace{ \frac{1}{n^{2}} }_{ 0 } \right)}   \\
 & a_{n}=\frac{\infty}{2} \\
 & \lim_{ n \to \infty }= +\infty
\end{align}
$$
---
### 2.
$$
\begin{align}
 & a_{n}=\frac{n^{2}+1}{3n^{3}+n-2} \\
 & a_{n}=\frac{\cancel{ n^{3} }\left( \frac{1}{n}+\frac{1}{n^{3}} \right)}{\cancel{ n^{3} }\left( 3+\frac{1}{n^{2}}-\frac{2}{n^{3}} \right)} \\
 & a_{n}=\frac{0}{3} \\
 & \lim_{ n \to \infty }=0 
\end{align}
$$
---
### 3.
$$
\begin{align}
 & a_{n}=\frac{(2n-1)^{2}}{(4n-1)(3n+2)} \\
 & a_{n}=\frac{4n^{2}-4n+1}{12n^{2}+8n-3n-2} \\
 & a_{n}=\frac{n^{2}\left( 4-\frac{4}{n}+1 \right)}{n^{2}\left( 12+\frac{5}{n}-\frac{2}{n^{2}} \right)} \\
 & a_{n}=\frac{5}{12} \\
 & \lim_{ n \to \infty } =\frac{5}{12}
\end{align}
$$
---
### 4.
$$
\begin{align}
 & a_{n}=\sqrt{ \frac{9n-1}{n+2} } \\
 & a_{n}=\sqrt{ \frac{\cancel{ n }\left( 9-\frac{1}{n} \right)}{\cancel{ n }\left( 1+\frac{2}{n} \right)} } \\
 & a_{n}=\frac{9}{1} \\
 & \lim_{ n \to \infty } =9
\end{align}
$$
---
### 5.
$$
\begin{align}
 & \lim_{ n \to \infty } =\frac{(2n+1)!+(2n+2)!}{(2n+3)!} \\
 & a_{n}=\frac{(2n+1)!+(2n+2)!}{(2n+3)(2n+2)(2n+1)!} \\
 & a_{n}=\frac{(2n+1)!+(2n+2)(2n+1)!}{(2n+3)(2n+2)(2n+1)!} \\
 & a_{n}=\frac{(2n+1)!·(1+2n+2)}{(2n+3)(2n+2)(2n+1)!} \\
 & a_{n}=\frac{1}{2n+2} \\
 & \lim_{ n \to \infty } =0
\end{align}
$$
---
### 6.
$$
\begin{align}
 & \lim_{ n \to \infty } =\sqrt{ n+4 }-\sqrt{ n-1 }  \\ \\
 & \text{Multiply by conjugate since the coefficients next to n are the same} \\
 & \lim_{ n \to \infty } = (\sqrt{ n+4 }-\sqrt{ n-1 }) · \frac{\sqrt{ n+4 }+\sqrt{ n-1 }}{\sqrt{ n+4 }+\sqrt{ n-1 }} \\
 & \lim_{ n \to \infty } =\frac{n+4+(\sqrt{ n+4 }·\sqrt{ n-1 })-(\sqrt{ n-1 }·\sqrt{ n+4 })-(n-1)}{\sqrt{ n+4 }+\sqrt{ n-1 }} \\
 & \lim_{ n \to \infty } = \frac{n+4-n+1}{\sqrt{ n+4 }+\sqrt{ n-1 }} \\
 & \lim_{ n \to \infty }=\frac{5}{\infty}  \\
 & \lim_{ n \to \infty } =0 
\end{align}
$$

---
### 7.
$$
\begin{align}
 & \lim_{ n \to \infty } =\sqrt{ n-100 }-\sqrt{ 2n } \\
 & \lim_{ n \to \infty } =\sqrt{ n }\left( \sqrt{ 1-\frac{100}{n} } \right)-\sqrt{ 2 }·\sqrt{ n } \\
 & \lim_{ n \to \infty } =\sqrt{ n }\left( \sqrt{ 1-\frac{100}{n} }-\sqrt{ 2 } \right) \\
 & \lim_{ n \to \infty } =\infty(1-\sqrt{ 2 })\\
 & \lim_{ n \to \infty } =-\infty \\
 &  \\
 & 
\end{align}
$$
---
### 8.
$$
\begin{align}
 & \lim_{ n \to \infty } =\frac{\sqrt{ n^{2}+25 }-n}{\sqrt{ n^{2}+16 }-n} \\
 & \lim_{ n \to \infty } = \frac{\sqrt{ n^{2}+25 }-n}{\sqrt{ n^{2}+16 }-n}· \frac{\frac{\sqrt{ n^{2}+25 }+n}{\sqrt{ n^{2}+25 }+n}}{\frac{\sqrt{ n^{2}+16 }+n}{\sqrt{ n^{2}+16 }+n}}  \\
 & \lim_{ n \to \infty } =\frac{\frac{\frac{n^{2}+25+n\sqrt{ n^{2}+25 }-n\sqrt{ n^{2}+25 }-n^{2}}{\sqrt{ n^{2}+25 }+n}}{n^{2}+16+n\sqrt{ n^{2}+16 }-n\sqrt{ n^{2}+16 }-n^{2}}}{\sqrt{ n^{2}+16 }+n} \\
 & \lim_{ n \to \infty } =\frac{\frac{25}{\sqrt{ n^{2}+25 }+n}}{\frac{16}{\sqrt{ n^{2}+16+n }}} \\
 & \lim_{ n \to \infty } =\frac{25}{\sqrt{ n^{2}+25 }+n}· \frac{\sqrt{ n^{2}+16 }+n}{16} \\
 & \lim_{ n \to \infty } =\frac{25\sqrt{ n^{2}+16 }+25n}{16\sqrt{ n^{2}+25 }+16n} \\
 & \lim_{ n \to \infty } =\frac{25}{16}· \frac{\sqrt{ n^{2}+16 }+n}{\sqrt{ n^{2}+25 }+n} \\
 & \lim_{ n \to \infty } =\frac{25}{16}· \frac{n\left( \sqrt{ 1+\frac{16}{n^{2}} }+1 \right)}{n\left( \sqrt{ 1+\frac{25}{n^{2}} }+1 \right)}  \\
 & \lim_{ n \to \infty } =\frac{25}{16}· \frac{2}{2} \\
 & \lim_{ n \to \infty } =\frac{25}{16} 
\end{align}
$$
---
### 9.
$$
\begin{align}
 & \lim_{ n \to \infty } = n(\sqrt{ 2n^{2}+1 }-\sqrt{ 2n^{2}-1 }) \\
 & \lim_{ n \to \infty }= n · (\sqrt{ 2n^{2}+1 }-\sqrt{ 2n^{2}-1 })· \frac{\sqrt{ 2n^{2}+1 }+\sqrt{ 2n^{2}-1 }}{\sqrt{ 2n^{2}+1 }+\sqrt{ 2n^{2}-1 }} \\
 & \lim_{ n \to \infty }= n·\frac{2n^{2}+1+\cancel{ \sqrt{ 2n^{2}+1 }·\sqrt{ 2n^{2}-1 }-\sqrt{ 2n^{2}-1 }·\sqrt{ 2n^{2}+1 } }-(2n^{2}-1)}{\sqrt{ 2n^{2}+1 }+\sqrt{ 2n^{2}-1 }} \\
 & \lim_{ n \to \infty } =n·\frac{2n^{2}+1-2n^{2}+1}{\sqrt{ 2n^{2}+1 }+\sqrt{ 2n^{2}-1 }} \\
 & \lim_{ n \to \infty } =n·\frac{2}{n\sqrt{ 2+\frac{1}{n^{2}} }+n\sqrt{ 2n-\frac{1}{n^{2}} }} \\
 & \lim_{ n \to \infty } =\frac{2}{\sqrt{ 2+\frac{1}{n^{2}} }+\sqrt{ 2-\frac{1}{n^{2}} }} \\
 & \lim_{ n \to \infty } =\frac{2}{2\sqrt{ 2 }} \\
 & \lim_{ n \to \infty } =\frac{1}{\sqrt{ 2 }} \\
 & \lim_{ n \to \infty } =\frac{\sqrt{ 2 }}{2}
\end{align}
$$
---
### 10.
$$
\begin{align}
 & \lim_{ n \to \infty } =\frac{n \overbrace{ \cos n! }^{ \text{undefined} }}{n^{2}+2}  \\
 & -1<\cos n!<1 /·n \\
 & -n<n\cos n!<n /:n^{2}+2 \\
 & -\frac{n}{n^{2}+2}< \frac{n\cos n!}{n^{2}+2}< \frac{n}{n^{2}+2} \\
 & \text{For large n,} \frac{n}{n^{2}+2}≈ \frac{n}{n^{2}}=\frac{1}{n}=0   \\
 &  0< \frac{n\cos n!}{n^{2}+2} <0 \\
 & \lim_{ n \to \infty } =0
\end{align}
$$---
### 11.
$$
\begin{align}
 & \lim_{ n \to \infty } =\sqrt[n]{1+3^n+7^n} \\
 & 7^{n}\leq\sqrt[n]{ 1+3^{n}+7^{n} }\leq s
\end{align}
$$

# Problem list 5
## 1 Calculate
1. $$
\begin{align}
 & \lim_{ x \to -2 } \frac{2x+4}{x^{3}+8}    \overset{\left[ \frac{0}{0} \right] }{=}  \\
 & \lim_{ x \to -2 } \frac{2(x+2)}{(x+2)(x^{2}-2x+4)} \\
 & \lim_{ x \to -2 } \frac{2}{\underbrace{ x^{2}-2x+4 }_{ 12 }} \\
 & \lim_{ x \to -2 } \frac{1}{6}
\end{align}
$$
2. $$
\begin{align}
 & \lim_{ x \to 3 } \frac{x^{2}-2x-3}{2x-6}  = \left[ \frac{0}{0} \right] \\
 & \lim_{ x \to 3 } \frac{(x-3)(x+1)}{2(x-3)} \\
 & \lim_{ x \to 3 } \frac{\overbrace{ x+1 }^{ 4 }}{2} \\
 & \lim_{ x \to 3 } =2
\end{align}
$$
3. $$
\begin{align}
 & \lim_{ x \to -1 } \frac{-2}{\underbrace{ (x+1)^{2} }_{0^{+}}}=\left[ \frac{-2}{0^{+}} \right]  \\
 & \lim_{ x \to -1 } =-\infty
\end{align}
$$
4. $$
\begin{align}
 & \lim_{ x \to 3 } \frac{2^{x}-8}{x-3}=\left[ \frac{0}{0} \right] \\
 & \begin{cases}
t=x-3 \\
x=t+3 \\
x\to 3 \implies t\to 0
\end{cases} \\
 & \lim_{ t \to 0 } \frac{2^{t+3}-8}{t+3-3} \\
 & \lim_{ t \to 0 } \frac{2^{3}·2^{t}-2^{3}}{t} \\
 & \lim_{ t \to 0 } 8·\frac{2^{t}-1}{t} \\
 & \lim_{ t \to 0 } =8\ln 2
\end{align}
$$
5. $$
\begin{align}
 & \lim_{ x \to 0 } \frac{\sin 2x}{\tan 5x}=\left[ \frac{0}{0} \right] \\
 & \lim_{ x \to 0 } \frac{\sin 2x}{\frac{\sin 5x}{\cos 5x}} \\
 & \lim_{ x \to 0 } \sin 2x· \frac{\cos 5x}{\sin 5x}  \\
 & \lim_{ x \to 0 } \frac{\sin(2x)}{2x}·2x·\cos(5x)·\frac{1}{\frac{\sin(5x)}{5x}·5x} \\
 & \lim_{ x \to 0 } 2x·\cos(5x)·\frac{1}{5x} \\
 & \lim_{ x \to 0 } =\frac{2}{5}
\end{align}
$$
6. $$
\begin{align}
 & \lim_{ x \to 0 } \frac{2\arcsin(3x)}{0.5x}  \\
 & \lim_{ x \to 0 } 4·\frac{\arcsin(3x)}{x} \\
 & \lim_{ x \to 0 } 4·\frac{\arcsin(3x)}{3x}·3 \\
 & \lim_{ x \to 0 } 4·3 \\
 & \lim_{ x \to 0 } =12  \\
\end{align}
$$
7. $$
\begin{align}
 & \lim_{ x \to \pi } \frac{\sin(4x)}{\sin(3x)} \\
 & \begin{cases}
t=\pi-x \\
x=\pi-t \\
x\to \pi \implies t \to 0
\end{cases}  \\
 & \lim_{ t \to 0 } \frac{\sin(4\pi-4t)}{\sin(3\pi-3t)} \\
 & \lim_{ t \to 0 } \frac{\sin(-4t)}{\sin(\pi-3t)} \\
 & \lim_{ t \to 0 } \frac{-\sin(4t)}{\sin(3t)} \\
 & \lim_{ t \to 0 } \frac{\frac{-\sin(4t)}{4t}·4t}{\frac{\sin(3t)}{3t}·3t} \\
 & \lim_{ t \to 0 }= \frac{-4}{3}
\end{align}
$$
8. $$
\begin{align}
 & \lim_{ x \to \frac{\pi}{2} } \frac{\cos(5x)}{\sin(10x)}= \\
 & \begin{cases}
t=\frac{\pi}{2}-x \\
x=\frac{\pi}{2}-t \\
x\to \frac{\pi}{2}\implies t\to 0
\end{cases} \\
 & \lim_{ t \to 0 } \frac{\cos\left( \frac{5\pi}{2}-5t \right)}{\sin(5\pi-10t)} \\
 & \lim_{ t \to 0 } \frac{\cos\left( \frac{\pi}{2}-5t \right)}{\sin(\pi-10t)} \\
 & \lim_{ t \to 0 } \frac{\sin\left( 5t \right)}{\sin(10t)} \\
 & \lim_{ t \to 0 } \frac{\frac{\sin(5t)}{5t}·5t}{\frac{\cos(10t)}{10t}·10t} \\
 & \lim_{ t \to 0 } =\frac{1}{2}
\end{align}
$$
9. $$
\begin{align}
 & \lim_{ x \to \frac{\pi}{2} } \frac{\sin(x)}{x} \\
 & \lim_{ x \to \frac{\pi}{2} } =\frac{1}{\frac{\pi}{2}} \\
 & \lim_{ x \to \frac{\pi}{2} } =\frac{2}{\pi}
\end{align}
$$
10. Don't get it$$
\begin{align}
 & \lim_{ x \to +\infty }xarccot(3x+1) \\
 & \begin{cases}
t=3x+1 \\
3x=t-1 \\
x=\frac{t-1}{3} \\
x\to \infty \implies t
\end{cases} \\
 & \lim_{ t \to +\infty } \frac{t-1}{3}arccot(t)
\end{align}
$$
11. $$
\begin{align}
 & \lim_{ x \to 0 } \frac{\sqrt{ x+1 }-1}{\sin(3x)} \\
 & \lim_{ x \to 0 } \frac{\sqrt{ x+1 }-1}{\frac{\sin(3x)}{3x}·3x} \\
 & \lim_{ x \to 0 } \frac{\sqrt{ x+1 }-1}{3x}·\frac{\sqrt{ x+1 }+1}{\sqrt{ x+1 }+1} \\
 & \lim_{ x \to 0 } \frac{x+1+\sqrt{ x+1 }-\sqrt{ x+1 }-1}{3x(\sqrt{ x+1 }+1)} \\
 & \lim_{ x \to 0 } \frac{\cancel{ x }}{3\cancel{ x }\underbrace{ (\sqrt{ x+1 }+1 }_{ 2 })} \\
 & \lim_{ x \to 0 } =\frac{1}{6}
\end{align}
$$
12. $$
\begin{align}
 & \lim_{ x \to 0 } \frac{\sqrt{ 1+\sin x }-\sqrt{ 1-\sin x }}{\tan x} \\
 & \lim_{ x \to 0 } \frac{\sqrt{ 1+x }-\sqrt{ 1-x }}{\frac{\sin x}{\cos x}} \\
 & \lim_{ x \to 0 } \frac{\sqrt{ 1+x }-\sqrt{ 1-x }}{\frac{x}{1}} \\
 & \lim_{ x \to 0 } \frac{\sqrt{ 1+x }-\sqrt{ 1-x }}{x}·\frac{\sqrt{ 1+x }+\sqrt{ 1-x }}{\sqrt{ 1+x }+\sqrt{ 1-x }} \\
 & \lim_{ x \to 0 } \frac{1+x+(\sqrt{ 1+x })(\sqrt{ 1-x })-(\sqrt{ 1+x })(\sqrt{ 1-x })-(1-x)}{x(\sqrt{ 1+x }+\sqrt{ 1-x })} \\
 & \lim_{ x \to 0 } \frac{1+x-1+x}{x(2)} \\
 & \lim_{ x \to 0 } \frac{2x}{2x} \\
 & \lim_{ x \to 0 } =1
\end{align}
$$
13. $$
\begin{align}
 & \lim_{ x \to 0 } \frac{x}{\sqrt{ 2x+1 }-1} =\\
 & \lim_{ x \to 0 } \frac{x}{\sqrt{ 2x+1 }-1}·\frac{\sqrt{ 2x+1 }+1}{\sqrt{ 2x+1+1 }}= \\
 & \lim_{ x \to 0 } \frac{x(\sqrt{ 2x+1 }+1)}{2x+1+\sqrt{ 2x+1 }-\sqrt{ 2x+1 }-1}= \\
 & \lim_{ x \to 0 } \frac{\cancel{ x }(\overbrace{ \sqrt{ 2x+1 }+1) }^{ 2 }}{2\cancel{ x }}= \\
 & \lim_{ x \to 0 } =\frac{2}{2}=1
\end{align}
$$
14. $$
\begin{align}
 & \lim_{ x \to 2 } \frac{x-\sqrt{ 3x-2 }}{x^{2}-4} \\
 & \begin{cases}
t=x-2 \\
x=t+2 \\
x\to 2 \implies t\to 0 
\end{cases} \\
 & \lim_{ t \to 0 } \frac{t+2-\sqrt{ 3t+6-2 }}{(t+2)^{2}-4} \\
 & \lim_{ t \to 0 } \frac{t+2-\sqrt{ 3t+6-2 }}{t^{2}+4t+4-4} \\
 & \lim_{ t \to 0 } \frac{t+2-\sqrt{ 3t+4 }}{t(t+4)}  \\
 & \lim_{ t \to 0 } \frac{t}{t(t+4)}+\frac{2-\sqrt{ 3t+4 }}{t(t+4)}·\frac{2+\sqrt{ 3t+4 }}{2+\sqrt{ 3t+4 }} \\
 & \lim_{ t \to 0 } \frac{1}{4}+\frac{4-(3t+4)}{2t(t+4)+t(t+4)(\sqrt{ 3t+4 })} \\
 & \lim_{ t \to 0 } \frac{1}{4}+\frac{-3\cancel{ t }}{\cancel{ t }(t+4)(2+\sqrt{ 3t+4 })} \\
 & \lim_{ t \to 0 } \frac{1}{4}-\frac{3}{16} \\
 & \lim_{ t \to 0 } =\frac{1}{16}
\end{align}
$$
15. $$
\begin{align}
 & \lim_{ x \to 0 } \frac{2-\sqrt{ 4+x }}{5-\sqrt{ 25+x }}  \\
 & \lim_{ x \to 0 } \frac{2-\sqrt{ 4+x }}{5-\sqrt{ 25+x }} · \frac{\frac{2+\sqrt{ 4+x }}{2+\sqrt{ 4+x }}}{\frac{5+\sqrt{ 25+x }}{5+\sqrt{ 25+x }}} \\
 & \lim_{ x \to 0 } \frac{\frac{4+2\sqrt{ 4+x }-2\sqrt{ 4+x }-(4+x)}{2+\sqrt{ 4+x }}}{\frac{25+5\sqrt{ 25+x }-5\sqrt{ 25+x }-(25+x)}{5+\sqrt{ 25+x }}} \\
 & \lim_{ x \to 0 } \frac{\frac{-x}{2+\sqrt{ 4+x }}}{\frac{-x}{5+\sqrt{ 25+x }}} \\
 & \lim_{ x \to 0 } \frac{\cancel{ -x }}{2+\sqrt{ 4+x }}·\frac{5+\sqrt{ 25+x }}{\cancel{ -x }} \\
 & \lim_{ x \to 0 } \frac{5+\sqrt{ 25+x }}{2+\sqrt{ 4+x }} \\
 & \lim_{ x \to 0 } = \frac{10}{4}
\end{align}
$$

 $\boxed{ if \ \alpha \to 0,\ then (1+\alpha)^{\frac{1}{\alpha}}\to e}$
1.$$
\begin{align}
 & \lim_{ x \to 0 } \frac{\sqrt{ x^{2}+1 }-\sqrt{ x+1 }}{1-\sqrt{ x+1 }} \\
 & \lim_{ x \to 0 } \frac{\sqrt{ x^{2}+1 }-\sqrt{ x+1 }}{1-\sqrt{ x+1 }} ·\frac{\frac{\sqrt{ x^{2}+1 }+\sqrt{ x+1 }}{\sqrt{ x^{2}+1 }+\sqrt{ x+1 }}}{\frac{1+\sqrt{ x+1 }}{1+\sqrt{ x+1 }}} \\
 & \lim_{ x \to 0 } \frac{\frac{x^{2}+1-x-1}{\sqrt{ x^{2}+1 }+\sqrt{ x+1 }}}{\frac{1-x-1}{1+\sqrt{ x+1 }}} \\
 & \lim_{ x \to 0 } \frac{x^{2}-x}{\sqrt{ x^{2}+1 }+\sqrt{ x+1 }}·\frac{1+\sqrt{ x+1 }}{-x} \\
 & \lim_{ x \to 0 } \frac{x-1}{\sqrt{ x^{2}+1 }+\sqrt{ x+1 }}·(-1-\sqrt{ x+1 }) \\
 & \lim_{ x \to 0 } \frac{-x-x(\sqrt{ x+1 })+1+\sqrt{ x+1 }}{\sqrt{ x^{2}+1 }+\sqrt{ x+1 }} \\
 & \lim_{ x \to 0 } =\frac{2}{2}
\end{align}
$$
2. $$
\begin{align}
 & \lim_{ x \to -\infty } \frac{\sqrt{ x^{2}-x+2 }}{x-1} \\
 & \lim_{ x \to -\infty } \frac{\sqrt{ x^{2}\left( 1-\frac{1}{x}+\frac{2}{x^{2}} \right) }}{x-1} \\ 
 & \boxed{ |x|=\begin{cases}
x  & for & x\geq 0 \\
-x & for & x<0
\end{cases}}\\
 & \lim_{ x \to -\infty } \frac{|x|·\left( \sqrt{ 1-\frac{1}{x}+\frac{2}{x^{2}} } \right)}{x\left( 1-\frac{1}{x} \right)}  \\
 & \lim_{ x \to -\infty } \frac{-1}{1}
\end{align}
$$

3. $$
\begin{align}
 & \lim_{ x \to -\infty } (\sqrt{ x^{2}+1 }+x) \\
 & \lim_{ x \to -\infty } \left( |x|·\sqrt{ 1+\frac{1}{x^{2}} }+x \right) \\
 & \lim_{ x \to -\infty } (-x+x) \\
 & \lim_{ x \to -\infty } =0 
\end{align}
$$
19. $$
 \begin{align}
 & \lim_{ x \to +\infty } (\sqrt{ x^{2}+3 }-\sqrt{ x^{2}-3 }) \\
 & \lim_{ x \to +\infty } \left( |x|·\sqrt{ 1+\frac{3}{x^{2}} }-|x|·\sqrt{ 1-\frac{3}{x^{2}} } \right) \\
 & \lim_{ x \to +\infty } (x-x) \\
 & \lim_{ x \to +\infty } =0
\end{align}
$$
20. $$

$$
21. $$
\begin{align}
 & \lim_{ x \to +\infty } \frac{5^{x}-7^{x}}{5^{x}-2^{x}}  \\
 & \lim_{ x \to +\infty } \frac{7^{x}\left( \frac{5^{x}}{7^{x}}-1 \right)}{7^{x}\left( \frac{5^{x}}{7^{x}}-\frac{2^{x}}{7^{x}} \right)}  \\
 & \lim_{ x \to +\infty } \frac{-1}{0^{+}}=-\infty
\end{align}
$$
22. nope$$
\begin{align}
 & \lim_{ x \to -\infty } \frac{3^{x}+2^{x+1}}{5^{x}-2^{x}}  \\
 & \lim_{ x \to -\infty } \frac{5^{x}\left( \frac{3^{x}}{5^{x}}+\frac{2^{x+1}}{5^{x}} \right)}{5^{x}\left( 1-\frac{2^{x}}{5^{x}} \right)} \\
 & \lim_{ x \to -\infty } \frac{\left( \frac{3}{5} \right)^{x}+\left( \frac{2}{5} \right)^{x} ·2}{1-\left( \frac{2}{5} \right)^{x}} 
\end{align}
$$
23. $$
\begin{align}
 & \lim_{ x \to 0 } (1+x)^{\frac{1}{3x}} \\
 & \lim_{ x \to 0 } \left[ \overbrace{ (1+x)^{\frac{1}{x}} }^{ e } \right]^{x·\frac{1}{3x}} \\
 & \lim_{ x \to 0 } e^{\frac{1}{3}}
\end{align}
$$
24. $$
\begin{align}
 & \lim_{ x \to 2 }(x-1)^{\frac{3}{2-x}}  \\
 & \\
 & \begin{cases}
t=x-2 \\
x=t+2 \\
x \to 2 \implies t\to 0
\end{cases}
\\ 
 & \lim_{ t \to 0 } (t+2-1)^{\frac{3}{2-t-2}} \\
 & \lim_{ t \to 0 } (1+t)^{\frac{3}{-t}} \\
 & \lim_{ t \to 0 } \left[\overbrace{  (1+t)^{\frac{1}{t}}  }^{ \to e }\right]^{t·\frac{3}{-t}} \\
 & \lim_{ t \to 0 } e^{-3}
\end{align}
$$
25. $$
\begin{align}
 & \lim_{ x \to +\infty } \left( \frac{3x-4}{3x+2} \right)^{x+1} \\
 & \lim_{ x \to +\infty } \left( \frac{3x+2-2-4}{3x+2} \right)^{x+1} \\
 & \lim_{ x \to +\infty } \left[ \overbrace{ \left( 1+\frac{-6}{3x+2} \right)^{\frac{3x+2}{-6}}  }^{ e }\right]^{\frac{-6}{3x+2}·(x+1)} \\
 & \lim_{ x \to +\infty } e^{\frac{-6x-6}{3x+2}} \\
 & \lim_{ x \to +\infty } e^{-2}
\end{align}
$$
26. $$
\begin{align}
 & \lim_{ x \to -\infty } \left( \frac{x^{2}+1}{x^{2}-2} \right)^{x^{2}} \\
 & \lim_{ x \to -\infty } \left( \frac{x^{2}-2+2+1}{x^{2}-2} \right)^{x^{2}} \\
 & \lim_{ x \to -\infty } \left( 1+\frac{3}{x^{2}-2} \right)^{x^{2}}
\end{align}
$$
$a_{n}=\sqrt{ n^{2}+1 }-\sqrt{ n^{2}+6n+11 }$

$$
f(x)=\begin{cases}
\ln(a+1)+\frac{8^{x}-1}{x} & x< 0 \\
\ln(a^{2}+3a+2x^{2}) & x\geq 0
\end{cases}
$$