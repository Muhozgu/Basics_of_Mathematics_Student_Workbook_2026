# Exercise 12 Solution

## Problem

For

$$
A=\begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix},
$$

compute $A^2$, $A^3$, and $A^4$, conjecture a formula for $A^n$, and prove the formula by induction.

## Solution

Calculate the first powers:

$$
A^2=AA=
\begin{pmatrix}
1 & 2 \\
0 & 1
\end{pmatrix}.
$$

$$
A^3=A^2A=
\begin{pmatrix}
1 & 3 \\
0 & 1
\end{pmatrix},
\qquad
A^4=A^3A=
\begin{pmatrix}
1 & 4 \\
0 & 1
\end{pmatrix}.
$$

The top-right entry equals the exponent, while the diagonal entries remain 1. This suggests

$$
A^n=\begin{pmatrix}
1 & n \\
0 & 1
\end{pmatrix}
\qquad (n\ge1).
$$

### Proof by induction

For $n=1$, the formula gives

$$
\begin{pmatrix}1&1\\0&1\end{pmatrix}=A,
$$

so it holds for the base case.

Assume it holds for some $n\ge1$:

$$
A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}.
$$

Multiplying by $A$ gives

$$
A^{n+1}=A^nA
=
\begin{pmatrix}1&n\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
=
\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.
$$

This is exactly the claimed formula with $n+1$ in place of $n$. Therefore, by induction, the formula holds for all integers $n\ge1$.

## Verification

The formula gives $A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix}$, $A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix}$, and $A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}$, agreeing with the calculations.

## Final Answer

$$
A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},
\qquad
A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},
\qquad
A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix},
$$

and, for every integer $n\ge1$,

$$
A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}.
$$
