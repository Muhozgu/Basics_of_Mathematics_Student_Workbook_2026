# Solution 2

We solve

$$
AX=I
$$
for

$$
A=\begin{pmatrix}1&1&0\\0&1&1\\0&0&1\end{pmatrix}.
$$

Augment the matrix with the identity:

$$
\left[\begin{array}{ccc|ccc} 1&1&0&1&0&0\\0&1&1&0&1&0\\0&0&1&0&0&1 \end{array}\right].
$$

Use row operations:

- $R_1 \leftarrow R_1-R_2$ gives
  $$
  \left[\begin{array}{ccc|ccc} 1&0&-1&1&-1&0\\0&1&1&0&1&0\\0&0&1&0&0&1 \end{array}\right]
  $$
- $R_2 \leftarrow R_2-R_3$ gives
  $$
  \left[\begin{array}{ccc|ccc} 1&0&-1&1&-1&0\\0&1&0&0&1&-1\\0&0&1&0&0&1 \end{array}\right]
  $$
- $R_1 \leftarrow R_1+R_3$ gives
  $$
  \left[\begin{array}{ccc|ccc} 1&0&0&1&-1&1\\0&1&0&0&1&-1\\0&0&1&0&0&1 \end{array}\right].
  $$

Therefore,

$$
A^{-1}=\begin{pmatrix}1&-1&1\\0&1&-1\\0&0&1\end{pmatrix}.
$$

A quick check shows

$$
A A^{-1}=I,
$$
so this is correct.
