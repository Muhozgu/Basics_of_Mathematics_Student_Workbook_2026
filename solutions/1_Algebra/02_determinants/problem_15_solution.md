# Exercise 15 Solution

## Problem
Let $A$ and $B$ be invertible $2\times2$ matrices with
$$
\det A=-2,\qquad \det B=3.
$$
Compute
$$
\det(B^{-1}A^TB).
$$
State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

## Solution
Use the multiplicative property of determinants:
$$
\det(B^{-1}A^TB)=\det(B^{-1})\det(A^T)\det(B).
$$

Now,
$$
\det(B^{-1})=\frac1{\det(B)}=\frac13,
$$

and for any square matrix,
$$
\det(A^T)=\det(A)=-2.
$$

Therefore,
$$
\det(B^{-1}A^TB)=\frac13\cdot(-2)\cdot3=-2.
$$

The factors involving $B$ cancel because
$$
\det(B^{-1})\det(B)=\frac{1}{\det(B)}\det(B)=1.
$$

## Final Answer
$$
\det(B^{-1}A^TB)=-2.
$$