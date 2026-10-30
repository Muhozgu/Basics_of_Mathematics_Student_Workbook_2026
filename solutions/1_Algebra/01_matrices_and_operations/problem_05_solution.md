# Exercise 5 Solution

## Problem

Let

$$
A=\begin{pmatrix}
2 & -1 \\
1 & 3
\end{pmatrix},
\qquad
x=\begin{pmatrix}
4 \\
2
\end{pmatrix}.
$$

Compute $Ax$ and express it as a linear combination of the columns of $A$.

## Idea

Each entry of $Ax$ is the dot product of a row of $A$ with $x$. Equivalently, if the columns of $A$ are $a_1$ and $a_2$, then multiplying by $x=(x_1,x_2)^T$ gives $Ax=x_1a_1+x_2a_2$.

## Solution

Compute the matrix-vector product:

$$
Ax=
\begin{pmatrix}
2\cdot4+(-1)\cdot2 \\
1\cdot4+3\cdot2
\end{pmatrix}
=
\begin{pmatrix}
6 \\
10
\end{pmatrix}.
$$

The columns of $A$ are

$$
a_1=\begin{pmatrix}2\\1\end{pmatrix},
\qquad
a_2=\begin{pmatrix}-1\\3\end{pmatrix}.
$$

Using the entries of $x$ as coefficients,

$$
Ax=4a_1+2a_2
=4\begin{pmatrix}2\\1\end{pmatrix}
+2\begin{pmatrix}-1\\3\end{pmatrix}
=\begin{pmatrix}8\\4\end{pmatrix}
+\begin{pmatrix}-2\\6\end{pmatrix}
=\begin{pmatrix}6\\10\end{pmatrix}.
$$

## Verification

The column-combination result matches the direct matrix-vector multiplication.

## Final Answer

$$
Ax=\begin{pmatrix}6\\10\end{pmatrix}
=4\begin{pmatrix}2\\1\end{pmatrix}
+2\begin{pmatrix}-1\\3\end{pmatrix}.
$$
