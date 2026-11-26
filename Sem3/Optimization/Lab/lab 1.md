```latex
\documentclass{article}
\usepackage{amsmath}
\begin{document}

\section{function} 
$y(x)=\frac{x^{2}+1}{\sqrt{ x+3 }-1} x \in [-1,1]$

\section{Golden section}
\begin{math}
\tau=\frac{\sqrt{ 5-1 }}{2}\approx 0.618 \\
x_{1}^{1}=b^{1}-\tau(b^{1}-a^{1}) \\
x_{2}^{1}=a^{1}+\tau(b^{1}-a^{1}) \\
\\
if \ f(x_{1}^{1})\geq f(x_{2}^{1}) \\
a^{k+1}=x_{1}^{k} \\
b^{k+1}=b^{k} \\
x_{1}^{k+1}=x_{2}^{k} \\
x_{2}^{k+1}=a^{k+1}-\tau(b^{k+1}-a^{k+1}) \\
\\
if \ f(x_{1}^{k})<f(x_{2}^{k}) \\
a^{k+1}=a^{k} \\
b^{k+1}=x_{2}^{k}\\
x_{1}^{k+1}=b^{k+1}-\tau(b^{k+1}-a^{k+1}) \\
x_{2}^{k+1}=x_{1}^{k} \\
\\
\text{stop condition } \\
b^{k+1}-a^{k+1}\leq \sigma
\\ 

\end{math}

\secton{iteration 1}


\section{Gradient method}
\frac{df}{dx}\left( \frac{x^{2}+1}{\sqrt{ x+3 }-1} \right)=\frac{3x^{2}-4(\sqrt{ x+3 }-3)x-1}{2\sqrt{ x+3 }(\sqrt{ x+3 }-1)^2}\\
\\
x^{k+1}=x^{k}-\alpha \frac{d}{dx}|_{x^{k}}\\

\text{stop condition} \\
|f(x^{k+1})-f(x^{k})|\leq \epsilon \\
\\
\section{Iteration 1}
\\
x^{0}=0 \\
\alpha=0.5 \\
\frac{df}{dx}_{x^{0}}= \dots \\
x^{1}=x^{0}+\frac{df}{dx}|_{x^{0}}=
```
