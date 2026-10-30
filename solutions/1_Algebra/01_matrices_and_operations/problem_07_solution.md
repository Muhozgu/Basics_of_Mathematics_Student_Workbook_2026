# Exercise 7 Solution

## Problem

For

$$
A=\begin{pmatrix}
2 & 1 \\
0 & 2
\end{pmatrix},
$$

compute $AI$, $IA$, $A+0$, $A^2$, and $A^3$. Explain the roles of the identity matrix $I$ and the zero matrix $0$, and describe the pattern in the powers of $A$.

## Idea

For a $2\times2$ matrix, the identity and zero matrices are

$$
I=\begin{pmatrix}1&0\\0&1\end{pmatrix},
\qquad
0=\begin{pmatrix}0&0\\0&0\end{pmatrix}.
$$

The identity matrix leaves a matrix unchanged under multiplication, while adding the zero matrix leaves it unchanged.

## Solution

Multiplying by the identity on either side gives

$$
AI=A=
\begin{pmatrix}2&1\\0&2\end{pmatrix},
\qquad
IA=A=
\begin{pmatrix}2&1\\0&2\end{pmatrix}.
$$

Adding the zero matrix gives

$$
A+0=
\begin{pmatrix}2&1\\0&2\end{pmatrix}.
$$

Compute the square:

$$
A^2=AA=
\begin{pmatrix}
2\cdot2+1\cdot0 & 2\cdot1+1\cdot2 \\
0\cdot2+2\cdot0 & 0\cdot1+2\cdot2
\end{pmatrix}
=
\begin{pmatrix}4&4\\0&4\end{pmatrix}.
$$

Then

$$
A^3=A^2A=
\begin{pmatrix}
4\cdot2+4\cdot0 & 4\cdot1+4\cdot2 \\
0\cdot2+4\cdot0 & 0\cdot1+4\cdot2
\end{pmatrix}
=
\begin{pmatrix}8&12\\0&8\end{pmatrix}.
$$

The diagonal entries double with each power, while the top-right entries are $1$, $4$, and $12$ for $A$, $A^2$, and $A^3$. The pattern is

$$
A^n=\begin{pmatrix}
2^n & n\,2^{n-1} \\
0 & 2^n
\end{pmatrix}
\qquad (n\ge1).
$$

## Verification

For $n=1$, the formula gives $\begin{pmatrix}2&1\\0&2\end{pmatrix}$; for $n=2$ it gives $\begin{pmatrix}4&4\\0&4\end{pmatrix}$; and for $n=3$ it gives $\begin{pmatrix}8&12\\0&8\end{pmatrix}$, matching the calculations.

## Final Answer

$$
AI=IA=A,\qquad A+0=A,
$$

$$
A^2=\begin{pmatrix}4&4\\0&4\end{pmatrix},
\qquad
A^3=\begin{pmatrix}8&12\\0&8\end{pmatrix}.
$$

The identity matrix is the multiplicative identity, and the zero matrix is the additive identity. The powers follow the displayed pattern for $A^n$.
