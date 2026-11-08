# Solution 7

We study

$$
\begin{cases}x+y=2\\x+ky=k+1\end{cases}
$$

for real $k$.

Subtract the two equations:

$$
(x+ky)-(x+y)=(k+1)-2,
$$

so

$$
(k-1)y=k-1.
$$

### Case 1: $k\neq 1$

Then $k-1\neq0$, so

$$
y=1.
$$

Substitute into $x+y=2$:

$$
x=1.
$$

Thus there is a unique solution:

$$
\boxed{(x,y)=(1,1)}.
$$

### Case 2: $k=1$

The system becomes

$$
\begin{cases}x+y=2\\x+y=2\end{cases},
$$

which is the same equation twice. Hence there are infinitely many solutions:

$$
 x=2-t,\quad y=t,\text{ for any } t\in\mathbb{R}.
$$

So the full classification is:

- if $k\neq 1$, the system has exactly one solution, $(1,1)$;
- if $k=1$, the system has infinitely many solutions, $(2-t,t)$.
