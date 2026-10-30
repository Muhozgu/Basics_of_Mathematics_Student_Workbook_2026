# Exercise 8 Solution

## Problem
Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$, and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

## Solution
By multiplicativity of the determinant,
$$
\det(AB)=\det(A)\det(B)=3(-5)=-15,
$$

and
$$
\det(BA)=\det(B)\det(A)=(-5)(3)=-15.
$$

The first two results are equal because multiplication of determinants commutes:
$$
\det(AB)=\det(A)\det(B)=\det(B)\det(A)=\det(BA).
$$
This does not mean $AB=BA$ as matrices; it means their determinants are equal.

Now,
$$
\det(A^{-1})=\frac1{\det(A)}=\frac13,
$$
so
$$
\det(A^{-1}B)=\det(A^{-1})\det(B)=\frac13(-5)=-\frac53.
$$

## Final Answer
$$
\det(AB)=-15,\qquad \det(BA)=-15,\qquad \det(A^{-1}B)=-\frac53.
$$