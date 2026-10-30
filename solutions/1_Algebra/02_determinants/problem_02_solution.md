# Exercise 2 Solution

## Problem
For
$$
A=\begin{pmatrix}1&2&-1\\0&3&4\\2&1&5\end{pmatrix},
$$
compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

## Solution
Using Sarrus' rule,
$$
\det A = 1\cdot3\cdot5 + 2\cdot4\cdot2 + (-1)\cdot0\cdot1
-\big[(-1)\cdot3\cdot2 + 1\cdot4\cdot1 + 5\cdot0\cdot2\big].
$$
So,
$$
\det A = 15+16+0-(-6+4+0)=31-(-2)=33.
$$

Check: subtract $2R_1$ from $R_3$:
$$
\begin{pmatrix}1&2&-1\\0&3&4\\0&-3&7\end{pmatrix}.
$$
This row operation does not change the determinant. Expanding along the first column gives
$$
\det A = 1\cdot\det\begin{pmatrix}3&4\\-3&7\end{pmatrix}
=3\cdot7-4\cdot(-3)=21+12=33.
$$

## Final Answer
$$
\det A = 33.
$$