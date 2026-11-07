# Solution 4

First calculate the product:

$$
AB =
\begin{pmatrix}
1 & 0 & 2 \\
1 & 3 & 1
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
1 & 2
\end{pmatrix}
=
\begin{pmatrix}
4 & 5 \\
3 & 0
\end{pmatrix}.
$$

Therefore,

$$
(AB)^T =
\begin{pmatrix}
4 & 3 \\
5 & 0
\end{pmatrix}.
$$

To verify the identity, transpose the factors and multiply in reverse order:

$$
B^T A^T =
\begin{pmatrix}
2 & 0 & 1 \\
1 & -1 & 2
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 3 \\
2 & 1
\end{pmatrix}
=
\begin{pmatrix}
4 & 3 \\
5 & 0
\end{pmatrix}
=(AB)^T.
$$