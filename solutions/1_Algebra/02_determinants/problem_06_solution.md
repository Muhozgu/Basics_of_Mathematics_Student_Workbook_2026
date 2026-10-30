# Exercise 6 Solution

## Problem
For
$$
A(t)=\begin{pmatrix}t&1\\2&t\end{pmatrix},
$$
find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

## Solution
A matrix is not invertible precisely when its determinant is zero. Compute:
$$
\det A(t)=t\cdot t-1\cdot2=t^2-2.
$$
Set this equal to zero:
$$
 t^2-2=0 \quad\Rightarrow\quad t^2=2 \quad\Rightarrow\quad t=\pm\sqrt2.
$$

So the matrix is not invertible when
$$
\boxed{t=\pm\sqrt2}.
$$

These are exactly the values for which the determinant vanishes.

## Final Answer
$$
\det A(t)=0 \text{ when } t=\pm\sqrt2,
$$
so the matrix is singular for those values.