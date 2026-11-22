\documentclass{article}
\usepackage{amsmath}
\begin{document}

\section{function} 
$ y(x)=\frac{x^{2}+1}{\sqrt{ x+3 }-1} x \in [-1,1] $

\section{Golden section}

\begin{math}
\tau=\frac{\sqrt{ 5-1 }}{2}\approx 0.618 \
x{1}^{1}=b^{1}-\tau(b^{1}-a^{1}) \
x{2}^{1}=a^{1}+\tau(b^{1}-1) \
\
if \ f(x{1}^{1})\geq f(x{2}^{1}) \
a^{k+1}=x{1}^{k} \
b^{k+1}=b^{k} \
x{1}^{k+1}=x{2}^{k} \
x{2}^{k+1}=a^{k+1}-\tau(b^{k+1}-a^{k+1}) \
\
if \ f(x{1}^{k})<f(x{2}^{k}) \
a^{k+1}=a^{k} \
b^{k+1}=x{2}^{k}\
x{1}^{k+1}=b^{k+1}-\tau(b^{k+1}-a^{k+1}) \
x{2}^{k+1}=x{1}^{k} \
\
\text{stop condition } \
b^{k+1}-a^{k+1}\leq \sigma
\ 
\
\end{math}
\end{document}