# Solution 8

We solve the homogeneous system

$$
\begin{cases}x+2y-z=0\\2x+4y-2z=0\end{cases}.
$$

Notice that the second equation is exactly twice the first:

$$
2(x+2y-z)=2x+4y-2z=0.
$$

So there is only one independent equation:

$$
x+2y-z=0.
$$

Solve for $x$:

$$
x=z-2y.
$$

Let $y=s$ and $z=t$. Then

$$
(x,y,z)=(t-2s,s,t).
$$

Write this as

$$
(t-2s,s,t)=s(-2,1,0)+t(1,0,1).
$$

Therefore the solution set is

$$
\boxed{\{s(-2,1,0)+t(1,0,1): s,t\in\mathbb{R}\}}.
$$

So the solution space is spanned by the two vectors

$$
\boxed{(-2,1,0)\quad\text{and}\quad(1,0,1)}.
$$
