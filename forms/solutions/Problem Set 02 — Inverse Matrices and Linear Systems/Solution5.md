# Solution 5

We solve

$$
\begin{cases}3x+y=11\\2x+y=8\end{cases}
$$

using the inverse-matrix method.

Write the system as

$$
A\mathbf{u}=\mathbf{b},\qquad A=\begin{pmatrix}3&1\\2&1\end{pmatrix},\quad\mathbf{u}=\begin{pmatrix}x\\y\end{pmatrix},\quad\mathbf{b}=\begin{pmatrix}11\\8\end{pmatrix}.
$$

From Problem 1,

$$
A^{-1}=\begin{pmatrix}1&-1\\-2&3\end{pmatrix}.
$$

Thus

$$
\mathbf{u}=A^{-1}\mathbf{b}=\begin{pmatrix}1&-1\\-2&3\end{pmatrix}\begin{pmatrix}11\\8\end{pmatrix}
=\begin{pmatrix}11-8\\-22+24\end{pmatrix}
=\begin{pmatrix}3\\2\end{pmatrix}.
$$

So

$$
\boxed{x=3,\, y=2}.
$$

Compare with direct subtraction:

$$
(3x+y)-(2x+y)=11-8\quad\Rightarrow\quad x=3.
$$

Then

$$
y=8-2x=8-6=2.
$$

The answers agree.
