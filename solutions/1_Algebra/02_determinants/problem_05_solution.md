# Exercise 5 Solution

## Problem
For
$$
A=\begin{pmatrix}1&2&3\\2&1&0\\-1&4&2\end{pmatrix},
$$
find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

## Solution
Use the row operations
$$
R_2\leftarrow R_2-2R_1,\qquad R_3\leftarrow R_3+R_1.
$$
These are row-replacement operations, so the determinant does not change.

The matrix becomes
$$
\begin{pmatrix}1&2&3\\0&-3&-6\\0&6&5\end{pmatrix}.
$$

Now apply
$$
R_3\leftarrow R_3+2R_2.
$$
Again, this does not change the determinant. The matrix becomes
$$
\begin{pmatrix}1&2&3\\0&-3&-6\\0&0&-7\end{pmatrix}.
$$

This is upper triangular, so
$$
\det A = 1\cdot(-3)\cdot(-7)=21.
$$

## Final Answer
$$
\det A = 21.
$$