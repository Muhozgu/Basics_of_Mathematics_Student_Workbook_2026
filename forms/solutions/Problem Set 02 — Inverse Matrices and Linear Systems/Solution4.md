# Solution 4

Solve

$$
\begin{cases} x+y+z=4 \\ 2x-y+z=8 \\ x+2y-z=-3 \end{cases}
$$

by Gaussian elimination.

From the first equation,

$$
 x=4-y-z.
$$

Substitute into the second equation:

$$
2(4-y-z)-y+z=8
$$

$$
8-2y-2z-y+z=8
$$

$$
-3y-z=0\quad\Rightarrow\quad z=-3y.
$$

Substitute into the third equation:

$$
(4-y-z)+2y-z=-3
$$

$$
4+y-2z=-3
$$

$$
y-2z=-7.
$$

Now substitute $z=-3y$:

$$
y-2(-3y)=-7
$$

$$
y+6y=-7
$$

$$
7y=-7\quad\Rightarrow\quad y=-1.
$$

Then

$$
z=-3y=3,
$$

and

$$
x=4-y-z=4+1-3=2.
$$

So the solution is

$$
\boxed{(2,-1,3)}.
$$

Now compute $z$ by Cramer’s rule. The coefficient matrix is

$$
A=\begin{pmatrix}1&1&1\\2&-1&1\\1&2&-1\end{pmatrix}.
$$

Its determinant is

$$
\det(A)=7.
$$

Replacing the third column with the constant vector gives

$$
A_z=\begin{pmatrix}1&1&4\\2&-1&8\\1&2&-3\end{pmatrix},
$$

with

$$
\det(A_z)=21.
$$

Therefore,

$$
z=\frac{\det(A_z)}{\det(A)}=\frac{21}{7}=3.
$$

This agrees with the Gaussian elimination result.
