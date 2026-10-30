# Exercise 4 Solution

## Problem

For

$$
A=\begin{pmatrix}
1 & 2 \\
0 & 1
\end{pmatrix},
\qquad
B=\begin{pmatrix}
2 & 0 \\
3 & 1
\end{pmatrix},
$$

compute $AB$ and $BA$. Determine whether they are equal and explain what the example shows about matrix multiplication.

## Idea

To multiply matrices, multiply each row of the first matrix by each column of the second matrix. The order of the factors matters: in general, $AB$ need not equal $BA$.

## Solution

First compute $AB$:

$$
AB=
\begin{pmatrix}
1\cdot2+2\cdot3 & 1\cdot0+2\cdot1 \\
0\cdot2+1\cdot3 & 0\cdot0+1\cdot1
\end{pmatrix}
=
\begin{pmatrix}
8 & 2 \\
3 & 1
\end{pmatrix}.
$$

Now compute $BA$:

$$
BA=
\begin{pmatrix}
2\cdot1+0\cdot0 & 2\cdot2+0\cdot1 \\
3\cdot1+1\cdot0 & 3\cdot2+1\cdot1
\end{pmatrix}
=
\begin{pmatrix}
2 & 4 \\
3 & 7
\end{pmatrix}.
$$

Since

$$
\begin{pmatrix}
8 & 2 \\
3 & 1
\end{pmatrix}
\ne
\begin{pmatrix}
2 & 4 \\
3 & 7
\end{pmatrix},
$$

we have $AB\ne BA$.

## Verification

For example, the top-left entry of $AB$ is $1\cdot2+2\cdot3=8$, while the top-left entry of $BA$ is $2\cdot1+0\cdot0=2$. Thus the products are different.

## Final Answer

$$
AB=\begin{pmatrix}8&2\\3&1\end{pmatrix},
\qquad
BA=\begin{pmatrix}2&4\\3&7\end{pmatrix},
\qquad AB\ne BA.
$$

This example shows that matrix multiplication is not commutative: reversing the order of the factors can change the result.
