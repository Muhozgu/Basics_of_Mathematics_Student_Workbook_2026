# Exercise 2 Solution

## Problem

For

$$
A=\begin{pmatrix}
1 & 2 \\
-1 & 3
\end{pmatrix},
\qquad
B=\begin{pmatrix}
4 & -2 \\
0 & 5
\end{pmatrix},
$$

compute $A+B$, $A-B$, and $3A-2B$. Explain why matrix addition is possible only for matrices of the same size.

## Idea

Matrix addition and subtraction are performed entry by entry. Scalar multiplication means multiplying every entry of a matrix by the scalar. Addition and subtraction require matrices of the same size so that entries in corresponding positions can be paired.

## Solution

### 1. Compute $A+B$

$$
A+B=
\begin{pmatrix}
1+4 & 2+(-2) \\
-1+0 & 3+5
\end{pmatrix}
=
\begin{pmatrix}
5 & 0 \\
-1 & 8
\end{pmatrix}.
$$

### 2. Compute $A-B$

$$
A-B=
\begin{pmatrix}
1-4 & 2-(-2) \\
-1-0 & 3-5
\end{pmatrix}
=
\begin{pmatrix}
-3 & 4 \\
-1 & -2
\end{pmatrix}.
$$

### 3. Compute $3A-2B$

First, multiply each matrix by its scalar:

$$
3A=
\begin{pmatrix}
3 & 6 \\
-3 & 9
\end{pmatrix},
\qquad
2B=
\begin{pmatrix}
8 & -4 \\
0 & 10
\end{pmatrix}.
$$

Then subtract the corresponding entries:

$$
3A-2B=
\begin{pmatrix}
3-8 & 6-(-4) \\
-3-0 & 9-10
\end{pmatrix}
=
\begin{pmatrix}
-5 & 10 \\
-3 & -1
\end{pmatrix}.
$$

### Why must matrices have the same size to be added?

Each entry in one matrix is added to the entry in the same row and column of the other matrix. This is possible only when both matrices have the same number of rows and columns. If their sizes differ, some entries have no corresponding partner, so their sum is undefined.

## Verification

All three results are $2\times2$ matrices, matching the sizes of $A$ and $B$. For example, the top-right entry of $3A-2B$ is $3(2)-2(-2)=10$, and its bottom-left entry is $3(-1)-2(0)=-3$.

## Final Answer

$$
A+B=
\begin{pmatrix}
5 & 0 \\
-1 & 8
\end{pmatrix},
\qquad
A-B=
\begin{pmatrix}
-3 & 4 \\
-1 & -2
\end{pmatrix},
$$

$$
3A-2B=
\begin{pmatrix}
-5 & 10 \\
-3 & -1
\end{pmatrix}.
$$
