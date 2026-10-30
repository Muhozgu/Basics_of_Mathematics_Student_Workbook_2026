# Exercise 11 Solution

## Problem

Given

$$
A=\begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix},
\qquad
B=\begin{pmatrix}
a & b \\
c & d
\end{pmatrix},
$$

find the conditions on $a,b,c,d$ for which $AB=BA$, and describe all such matrices $B$.

## Solution

Compute both products:

$$
AB=
\begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix}
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
=
\begin{pmatrix}
a+c & b+d \\
c & d
\end{pmatrix}.
$$

$$
BA=
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix}
=
\begin{pmatrix}
a & a+b \\
c & c+d
\end{pmatrix}.
$$

For these matrices to be equal, corresponding entries must be equal. The top-left entries give $a+c=a$, so $c=0$. The top-right entries give $b+d=a+b$, so $d=a$. The bottom entries give the same condition $c=0$.

There is no restriction on $b$. Thus the conditions are $c=0$ and $d=a$, and the matrices that commute with $A$ have the form

$$
B=\begin{pmatrix}
a & b \\
0 & a
\end{pmatrix},
\qquad a,b\in\mathbb{R}.
$$

## Verification

Substituting $c=0$ and $d=a$ gives

$$
AB=BA=\begin{pmatrix}a& a+b\\0&a\end{pmatrix}.
$$

## Final Answer

$$
AB=BA
\quad\Longleftrightarrow\quad
c=0,\ d=a,
\qquad
B=\begin{pmatrix}a&b\\0&a\end{pmatrix}.
$$
