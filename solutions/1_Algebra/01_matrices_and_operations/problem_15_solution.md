# Exercise 15 Solution

## Problem

Given

$$
A=\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1
\end{pmatrix},
\qquad
B=\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3
\end{pmatrix},
\qquad
C=\begin{pmatrix}
2 & 1 \\
0 & -1
\end{pmatrix},
$$

compute $(AB)C$ and $A(BC)$. Compare the results and calculation paths, and explain associativity.

## Solution

### First path: compute $(AB)C$

First,

$$
AB=
\begin{pmatrix}
1\cdot1+2\cdot2+0\cdot(-1) & 1\cdot0+2\cdot1+0\cdot3 \\
0\cdot1+1\cdot2+1\cdot(-1) & 0\cdot0+1\cdot1+1\cdot3
\end{pmatrix}
=
\begin{pmatrix}
5 & 2 \\
1 & 4
\end{pmatrix}.
$$

Then,

$$
(AB)C=
\begin{pmatrix}
5 & 2 \\
1 & 4
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1
\end{pmatrix}
=
\begin{pmatrix}
10 & 3 \\
2 & -3
\end{pmatrix}.
$$

### Second path: compute $A(BC)$

First,

$$
BC=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1
\end{pmatrix}
=
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4
\end{pmatrix}.
$$

Then,

$$
A(BC)=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4
\end{pmatrix}
=
\begin{pmatrix}
10 & 3 \\
2 & -3
\end{pmatrix}.
$$

Both calculation paths give the same result:

$$
(AB)C=A(BC)=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
$$

## Comparison and Associativity

Each path uses two matrix multiplications: one intermediate product and one final product. The intermediate matrices differ: $AB$ has size $2\times2$, while $BC$ has size $3\times2$. With the usual row-by-column method, computing $(AB)C$ requires 20 scalar multiplications and 12 additions, while computing $A(BC)$ requires 24 scalar multiplications and 14 additions. Thus, for these dimensions, computing $AB$ first takes fewer scalar operations.

Associativity means the grouping of a product can change without changing its value: $(AB)C=A(BC)$. It does not mean that the order of the matrices can be changed.

## Verification

The two independently calculated products both equal the same $2\times2$ matrix, confirming associativity in this example.

## Final Answer

$$
(AB)C=A(BC)=
\begin{pmatrix}
10 & 3 \\
2 & -3
\end{pmatrix}.
$$
