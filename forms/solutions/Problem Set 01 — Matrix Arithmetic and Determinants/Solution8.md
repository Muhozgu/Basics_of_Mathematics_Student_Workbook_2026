# Solution 8

To find the minor $M_{23}$, delete row $2$ and column $3$ of $A$. The
remaining $2\times2$ matrix is

$$
\begin{pmatrix}
2 & 1 \\
1 & 0
\end{pmatrix},
$$

so

$$
M_{23}
=
\begin{vmatrix}
2 & 1 \\
1 & 0
\end{vmatrix}
=2(0)-1(1)
=-1.
$$

The cofactor includes the sign factor $(-1)^{i+j}$:

$$
C_{23}=(-1)^{2+3}M_{23}=(-1)(-1)=1.
$$

Thus $\boxed{M_{23}=-1}$ and $\boxed{C_{23}=1}$. They have opposite signs
because position $(2,3)$ has an odd row-plus-column index, so its cofactor
sign is negative.