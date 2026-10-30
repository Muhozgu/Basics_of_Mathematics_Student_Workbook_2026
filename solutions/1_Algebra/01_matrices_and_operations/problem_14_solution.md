# Exercise 14 Solution

## Problem

The rotation matrix through an angle $\theta$ is

$$
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta
\end{pmatrix}.
$$

Compute $R(\alpha)R(\beta)$ and show that it equals $R(\alpha+\beta)$. Explain the result geometrically.

## Solution

Write out the product:

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha & -\sin\alpha \\
\sin\alpha & \cos\alpha
\end{pmatrix}
\begin{pmatrix}
\cos\beta & -\sin\beta \\
\sin\beta & \cos\beta
\end{pmatrix}.
$$

Multiplying gives

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta
&
-\cos\alpha\sin\beta-\sin\alpha\cos\beta
\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta
&
-\sin\alpha\sin\beta+\cos\alpha\cos\beta
\end{pmatrix}.
$$

Using the angle-sum identities

$$
\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta,
\qquad
\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta,
$$

the product becomes

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta) \\
\sin(\alpha+\beta) & \cos(\alpha+\beta)
\end{pmatrix}
=R(\alpha+\beta).
$$

## Geometric Explanation

Applying $R(\beta)$ rotates a vector by $\beta$, and then applying $R(\alpha)$ rotates the result by $\alpha$. The total rotation is therefore $\alpha+\beta$, which is exactly what $R(\alpha+\beta)$ does.

## Verification

The four entries of the product match the cosine and sine angle-sum formulas, including the negative sign in the top-right entry.

## Final Answer

$$
R(\alpha)R(\beta)=R(\alpha+\beta).
$$
