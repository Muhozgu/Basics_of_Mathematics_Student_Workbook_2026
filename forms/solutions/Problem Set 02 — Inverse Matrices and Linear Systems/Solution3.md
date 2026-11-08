# Solution 3

We use Cramer’s rule on

$$
\begin{cases} 2x+y=7 \\ x-y=2 \end{cases}
$$

The coefficient matrix is

$$
A=\begin{pmatrix}2&1\\1&-1\end{pmatrix},\qquad\det(A)=2(-1)-1(1)=-3\neq0.
$$

Since the determinant is nonzero, Cramer’s rule applies.

For $x$:

$$
\det(A_x)=\begin{vmatrix}7&1\\2&-1\end{vmatrix}=7(-1)-1(2)=-9,
$$

so

$$
x=\frac{-9}{-3}=3.
$$

For $y$:

$$
\det(A_y)=\begin{vmatrix}2&7\\1&2\end{vmatrix}=2(2)-7(1)=-3,
$$

so

$$
y=\frac{-3}{-3}=1.
$$

Hence, the solution is

$$
\boxed{(x,y)=(3,1)}.
$$

Check:

$$
2(3)+1=7,\qquad 3-1=2.
$$
