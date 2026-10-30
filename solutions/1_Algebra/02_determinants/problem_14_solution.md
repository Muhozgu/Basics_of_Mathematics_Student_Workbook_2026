# Exercise 14 Solution

## Problem
Consider the system $Ax=b$, where
$$
A=\begin{pmatrix}1&2\\k&4\end{pmatrix}.
$$
For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

## Solution
A $2\times2$ system has exactly one solution for every right-hand side when the determinant is nonzero:
$$
\det A = 1\cdot4-2k = 4-2k.
$$
Thus,
$$
4-2k\neq0\quad\Rightarrow\quad k\neq2.
$$

So for all $k\neq2$, the system has a unique solution for every $b$.

When $k=2$, the matrix becomes singular. The system is then
$$
\begin{cases}x+2y=b_1,\\2x+4y=b_2.
\end{cases}
$$
The second equation is $2$ times the first, so the system may have infinitely many solutions or none.

Example with infinitely many solutions:
$$
 b=\begin{pmatrix}1\\2\end{pmatrix},
$$
which gives
$$
\begin{cases}x+2y=1,\\2x+4y=2,
\end{cases}
$$
which are the same equation.

Example with no solution:
$$
 b=\begin{pmatrix}1\\3\end{pmatrix},
$$
which gives
$$
\begin{cases}x+2y=1,\\2x+4y=3.
\end{cases}
$$
The second equation contradicts the first because it would require $2(x+2y)=3$ while the first gives $x+2y=1$.

## Final Answer
The system has exactly one solution for every $b$ when $k\neq2$. For $k=2$, the system is singular: it has infinitely many solutions for $b=(1,2)^T$, and no solution for $b=(1,3)^T$.