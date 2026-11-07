# Solution 9

Expand along the first row. The cofactor signs in that row are $+,-,+$:

$$
\begin{aligned}
\det\begin{pmatrix}
0 & 2 & 0 \\
1 & -1 & 3 \\
4 & 0 & 2
\end{pmatrix}
&=
0\begin{vmatrix}-1&3\\0&2\end{vmatrix}
-2\begin{vmatrix}1&3\\4&2\end{vmatrix}
+0\begin{vmatrix}1&-1\\4&0\end{vmatrix}\\
&=-2\bigl(1(2)-3(4)\bigr)\\
&=-2(-10)=20.
\end{aligned}
$$

Check by expanding down the first column. Its cofactor signs are again
$+,-,+$:

$$
\begin{aligned}
\det\begin{pmatrix}
0 & 2 & 0 \\
1 & -1 & 3 \\
4 & 0 & 2
\end{pmatrix}
&=
0\begin{vmatrix}2&0\\0&2\end{vmatrix}
-1\begin{vmatrix}2&0\\4&2\end{vmatrix}
+4\begin{vmatrix}2&0\\-1&3\end{vmatrix}\\
&=-1(4)+4(6)\\
&=-4+24=\boxed{20}.
\end{aligned}
$$

Both expansions give the same determinant, $\boxed{20}$.