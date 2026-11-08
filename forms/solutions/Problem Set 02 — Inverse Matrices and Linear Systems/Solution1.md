# Solution 1

For

$$
A = \begin{pmatrix} 3 & 1 \\ 2 & 1 \end{pmatrix},
$$

the determinant is

$$
\det(A)=3\cdot1-1\cdot2=1.
$$

So the inverse is

$$
A^{-1}=\frac{1}{\det(A)}\begin{pmatrix} 1 & -1 \\ -2 & 3 \end{pmatrix}=\begin{pmatrix} 1 & -1 \\ -2 & 3 \end{pmatrix}.
$$

Now check the product:

$$
AA^{-1}=\begin{pmatrix}3&1\\2&1\end{pmatrix}\begin{pmatrix}1&-1\\-2&3\end{pmatrix}
=\begin{pmatrix}3-2&-3+3\\2-2&-2+3\end{pmatrix}
=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I.
$$

Hence,

$$
\boxed{A^{-1}=\begin{pmatrix}1&-1\\-2&3\end{pmatrix}}.
$$
