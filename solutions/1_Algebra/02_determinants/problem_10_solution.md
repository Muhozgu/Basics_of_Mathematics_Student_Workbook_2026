# Exercise 10 Solution

## Problem
Without carrying out a full determinant calculation, explain why
$$
\det\begin{pmatrix}1&2&3\\2&4&6\\0&1&5\end{pmatrix}=0.
$$
Identify a specific dependence between the rows and connect it with noninvertibility.

## Solution
Notice that the second row is exactly twice the first row:
$$
[2,4,6]=2[1,2,3].
$$
So the rows are linearly dependent. A matrix with linearly dependent rows cannot be invertible, and therefore its determinant must be zero.

Hence,
$$
\det\begin{pmatrix}1&2&3\\2&4&6\\0&1&5\end{pmatrix}=0.
$$

## Final Answer
The second row is a multiple of the first, so the rows are dependent and the matrix is not invertible. Therefore, the determinant is zero.