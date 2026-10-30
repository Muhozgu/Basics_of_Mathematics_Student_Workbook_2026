# Exercise 11 Solution

## Problem
Compute
$$
\det\begin{pmatrix}1&2&3\\1&3&4\\1&4&6\end{pmatrix}
$$
by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

## Solution
Use the row-replacement operations
$$
R_2\leftarrow R_2-R_1,\qquad R_3\leftarrow R_3-R_1.
$$
These do not change the determinant. The matrix becomes
$$
\begin{pmatrix}1&2&3\\0&1&1\\0&2&3\end{pmatrix}.
$$

Now do
$$
R_3\leftarrow R_3-2R_2,
$$
which also does not change the determinant. Then
$$
\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix}.
$$

This is upper triangular, so
$$
\det=1\cdot1\cdot1=1.
$$

## Final Answer
$$
\det\begin{pmatrix}1&2&3\\1&3&4\\1&4&6\end{pmatrix}=1.
$$