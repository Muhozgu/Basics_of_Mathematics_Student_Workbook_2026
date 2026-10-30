# Exercise 12 Solution

## Problem
For
$$
A(t)=\begin{pmatrix}1&2&3\\2&4&t\\0&1&1\end{pmatrix},
$$
find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation
$$
R_2\leftarrow R_2-2R_1
$$
and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

## Solution
Apply the row operation:
$$
R_2\leftarrow R_2-2R_1.
$$
This does not change the determinant, and we get
$$
\begin{pmatrix}1&2&3\\0&0&t-6\\0&1&1\end{pmatrix}.
$$

Now expand along the first column to get
$$
\det A(t)=1\cdot\det\begin{pmatrix}0&t-6\\1&1\end{pmatrix}
=0\cdot1-(t-6)\cdot1=-(t-6).
$$
Therefore,
$$
\det A(t)=0 \quad\Longleftrightarrow\quad t=6.
$$

So the matrix is not invertible when
$$
\boxed{t=6}.
$$

At $t=6$, the new second row becomes $[0,0,0]$, so the rows are dependent.

## Final Answer
$$
\boxed{t=6}
$$
for which the matrix is singular.