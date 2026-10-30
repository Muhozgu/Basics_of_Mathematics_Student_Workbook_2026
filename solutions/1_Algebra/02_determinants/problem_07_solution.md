# Exercise 7 Solution

## Problem
Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute
$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$
Justify each answer using the appropriate property.

## Solution
Use the standard determinant rules:

- $\det(kA)=k^n\det(A)$ for an $n\times n$ matrix,
- $\det(A^T)=\det(A)$,
- $\det(A^2)=\det(A)^2$,
- $\det(-A)=(-1)^n\det(A)$.

Since $A$ is $3\times3$ and $\det A=-4$:

$$
\det(2A)=2^3\det(A)=8(-4)=-32,
$$

$$
\det(A^T)=\det(A)=-4,
$$

$$
\det(A^2)=\det(A)^2=(-4)^2=16,
$$

$$
\det(-A)=(-1)^3\det(A)=-1(-4)=4.
$$

## Final Answer
$$
\det(2A)=-32,\quad \det(A^T)=-4,\quad \det(A^2)=16,\quad \det(-A)=4.
$$