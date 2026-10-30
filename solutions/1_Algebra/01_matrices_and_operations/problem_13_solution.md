# Exercise 13 Solution

## Problem

Let

$$
F=\begin{pmatrix}
1 & 1 \\
1 & 0
\end{pmatrix}.
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Relate the entries to the Fibonacci sequence $0,1,1,2,3,5,8,\ldots$, and explain how $F$ performs one recurrence step on a vector.

## Solution

Multiply successively by $F$:

$$
F^2=
\begin{pmatrix}2&1\\1&1\end{pmatrix},
\qquad
F^3=
\begin{pmatrix}3&2\\2&1\end{pmatrix},
$$

$$
F^4=
\begin{pmatrix}5&3\\3&2\end{pmatrix},
\qquad
F^5=
\begin{pmatrix}8&5\\5&3\end{pmatrix}.
$$

Let $F_0=0$, $F_1=1$, and $F_{k+1}=F_k+F_{k-1}$. These results follow the pattern

$$
F^n=
\begin{pmatrix}
F_{n+1} & F_n \\
F_n & F_{n-1}
\end{pmatrix}
\qquad (n\ge1).
$$

For instance, the top-left entries of $F^1,F^2,F^3,F^4,F^5$ are $1,2,3,5,8$, consecutive Fibonacci numbers, and the other entries also appear in consecutive positions of the sequence.

For a vector with consecutive terms $a$ and $b$,

$$
F\begin{pmatrix}a\\b\end{pmatrix}
=
\begin{pmatrix}
1&1\\
1&0
\end{pmatrix}
\begin{pmatrix}a\\b\end{pmatrix}
=
\begin{pmatrix}a+b\\a\end{pmatrix}.
$$

The new first component is the sum of the two terms, and the second component keeps the previous first term. Thus one multiplication performs one Fibonacci recurrence step.

## Verification

For example, starting with the consecutive terms $(1,0)^T$ and repeatedly applying $F$ produces $(1,1)^T$, $(2,1)^T$, $(3,2)^T$, $(5,3)^T$, and $(8,5)^T$, matching the columns displayed in the powers.

## Final Answer

$$
F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix},
\quad
F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix},
\quad
F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix},
\quad
F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix},
$$

$$
F\begin{pmatrix}a\\b\end{pmatrix}
=
\begin{pmatrix}a+b\\a\end{pmatrix}.
$$
