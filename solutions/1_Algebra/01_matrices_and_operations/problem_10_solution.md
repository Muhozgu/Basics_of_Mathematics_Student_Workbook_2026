# Exercise 10 Solution

## Problem

Given

$$
A=\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1
\end{pmatrix},
\qquad
B=\begin{pmatrix}
1 & 2 \\
-1 & 0 \\
3 & 1
\end{pmatrix},
$$

let $b_1$ and $b_2$ be the columns of $B$.

1. Compute $Ab_1$ and $Ab_2$.
2. Compute $AB$.
3. Explain why the columns of $AB$ are $Ab_1$ and $Ab_2$.

## Idea

When a matrix multiplies another matrix, it acts on each column of the second matrix. If $B=(b_1\ b_2)$, then $AB=(Ab_1\ Ab_2)$.

## Solution

The columns of $B$ are

$$
b_1=\begin{pmatrix}1\\-1\\3\end{pmatrix},
\qquad
b_2=\begin{pmatrix}2\\0\\1\end{pmatrix}.
$$

Compute the first column:

$$
Ab_1=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1
\end{pmatrix}
\begin{pmatrix}1\\-1\\3\end{pmatrix}
=
\begin{pmatrix}
1-2+0 \\
0-1+3
\end{pmatrix}
=
\begin{pmatrix}-1\\2\end{pmatrix}.
$$

Compute the second column:

$$
Ab_2=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1
\end{pmatrix}
\begin{pmatrix}2\\0\\1\end{pmatrix}
=
\begin{pmatrix}
2+0+0 \\
0+0+1
\end{pmatrix}
=
\begin{pmatrix}2\\1\end{pmatrix}.
$$

Therefore, placing these two vectors side by side gives

$$
AB=
\begin{pmatrix}
-1 & 2 \\
2 & 1
\end{pmatrix}.
$$

## Explanation and Verification

The first column of $AB$ is $Ab_1$, and its second column is $Ab_2$. This follows from the definition of matrix multiplication: each column of the product is obtained by multiplying $A$ by the corresponding column of $B$. The direct product gives

$$
AB=
\begin{pmatrix}
1\cdot1+2\cdot(-1)+0\cdot3 & 1\cdot2+2\cdot0+0\cdot1 \\
0\cdot1+1\cdot(-1)+1\cdot3 & 0\cdot2+1\cdot0+1\cdot1
\end{pmatrix}
=
\begin{pmatrix}-1&2\\2&1\end{pmatrix},
$$

which matches the two column calculations.

## Final Answer

$$
Ab_1=\begin{pmatrix}-1\\2\end{pmatrix},
\qquad
Ab_2=\begin{pmatrix}2\\1\end{pmatrix},
\qquad
AB=\begin{pmatrix}-1&2\\2&1\end{pmatrix}.
$$
