# Solution 3

Compute each product by taking row-by-column dot products:

$$
AB =
\begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix}
\begin{pmatrix}
3 & 0 \\
2 & 1
\end{pmatrix}
=
\begin{pmatrix}
1(3)+1(2) & 1(0)+1(1) \\
0(3)+1(2) & 0(0)+1(1)
\end{pmatrix}
=
\begin{pmatrix}
5 & 1 \\
2 & 1
\end{pmatrix}.
$$

In the reverse order,

$$
BA =
\begin{pmatrix}
3 & 0 \\
2 & 1
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix}
=
\begin{pmatrix}
3 & 3 \\
2 & 3
\end{pmatrix}.
$$

Since $AB \ne BA$, matrix multiplication does not commute for this pair.