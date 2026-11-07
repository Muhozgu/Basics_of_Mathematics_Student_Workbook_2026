# Solution 7

Sarrus' rule applies because the matrix is a $3\times3$ square matrix. The
sum of the downward diagonal products is

$$
2(3)(4)+1(2)(1)+0(-1)(0)=24+2+0=26.
$$

The sum of the upward diagonal products is

$$
0(3)(1)+2(2)(0)+1(-1)(4)=0+0-4=-4.
$$

Subtracting the second sum from the first gives

$$
\det\begin{pmatrix}
2 & 1 & 0 \\
-1 & 3 & 2 \\
1 & 0 & 4
\end{pmatrix}
=26-(-4)
=\boxed{30}.
$$