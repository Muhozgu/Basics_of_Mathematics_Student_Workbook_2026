# Exercise 9 Solution

## Problem

Let

$$
S=\begin{pmatrix}
2 & 0 \\
0 & 1
\end{pmatrix},
\qquad
R=\begin{pmatrix}
0 & -1 \\
1 & 0
\end{pmatrix},
\qquad
x=\begin{pmatrix}
1 \\
2
\end{pmatrix}.
$$

Compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order matters.

## Idea

In a matrix product, the rightmost matrix acts first. Here $S$ stretches horizontally by a factor of 2, while $R$ rotates vectors $90^\circ$ counterclockwise.

## Solution

First apply $S$ to $x$:

$$
Sx=
\begin{pmatrix}
2 & 0 \\
0 & 1
\end{pmatrix}
\begin{pmatrix}1\\2\end{pmatrix}
=
\begin{pmatrix}2\\2\end{pmatrix}.
$$

Then rotate:

$$
RSx=
\begin{pmatrix}
0 & -1 \\
1 & 0
\end{pmatrix}
\begin{pmatrix}2\\2\end{pmatrix}
=
\begin{pmatrix}-2\\2\end{pmatrix}.
$$

For the other order, rotate first:

$$
Rx=
\begin{pmatrix}
0 & -1 \\
1 & 0
\end{pmatrix}
\begin{pmatrix}1\\2\end{pmatrix}
=
\begin{pmatrix}-2\\1\end{pmatrix}.
$$

Then apply the horizontal stretch:

$$
SRx=
\begin{pmatrix}
2 & 0 \\
0 & 1
\end{pmatrix}
\begin{pmatrix}-2\\1\end{pmatrix}
=
\begin{pmatrix}-4\\1\end{pmatrix}.
$$

Therefore,

$$
RSx=\begin{pmatrix}-2\\2\end{pmatrix}
\ne
\begin{pmatrix}-4\\1\end{pmatrix}=SRx.
$$

## Geometric Explanation

Stretching horizontally and then rotating is different from rotating first and then stretching horizontally. In the first order, the stretch affects the vector's original horizontal component before rotation. In the second order, rotation changes which direction the vector points before the horizontal stretch is applied.

## Verification

Direct multiplication gives

$$
RS=\begin{pmatrix}0&-1\\2&0\end{pmatrix},
\qquad
SR=\begin{pmatrix}0&-2\\1&0\end{pmatrix}.
$$

Thus $RSx=(-2,2)^T$ and $SRx=(-4,1)^T$, consistent with the step-by-step calculations.

## Final Answer

$$
RSx=\begin{pmatrix}-2\\2\end{pmatrix},
\qquad
SRx=\begin{pmatrix}-4\\1\end{pmatrix}.
$$

The results differ because the order of a stretch and a rotation changes the transformation applied to the vector.
