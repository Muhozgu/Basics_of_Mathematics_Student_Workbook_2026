# Exercise 13 Solution

## Problem
Compute the determinant of
$$
A=\begin{pmatrix}1&2&3\\2&5&7\\1&0&2\end{pmatrix}
$$
using elimination. Record the effect of every row operation used on the value of the determinant.

## Solution
Use row operations:
$$
R_2\leftarrow R_2-2R_1=[0,1,1],
$$
$$
R_3\leftarrow R_3-R_1=[0,-2,-1].
$$
These are row-replacement operations, so they do not change the determinant.

The matrix becomes
$$
\begin{pmatrix}1&2&3\\0&1&1\\0&-2&-1\end{pmatrix}.
$$

Now do
$$
R_3\leftarrow R_3+2R_2,
$$
which again does not change the determinant. Then
$$
\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix}.
$$

This is upper triangular, so
$$
\det A=1\cdot1\cdot1=1.
$$

## Final Answer
$$
\det A = 1.
$$