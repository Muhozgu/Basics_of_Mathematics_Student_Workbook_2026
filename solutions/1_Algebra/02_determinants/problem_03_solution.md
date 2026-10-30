# Exercise 3 Solution

## Problem
For
$$
A=\begin{pmatrix}1&2&0\\0&3&1\\2&1&1\end{pmatrix},
$$
compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$. First predict $\det B$ using a determinant property, and then verify by calculation.

## Solution
First,
$$
\det A = 1(3\cdot1-1\cdot1)-2(0\cdot1-1\cdot2)+0
=1(3-1)-2(0-2)=2+4=6.
$$
So,
$$
\det A=6.
$$

Now swap the first and second rows:
$$
B=\begin{pmatrix}0&3&1\\1&2&0\\2&1&1\end{pmatrix}.
$$
Swapping two rows changes the sign of the determinant, so
$$
\det B = -\det A=-6.
$$

Check:
$$
\det B = 0(2\cdot1-0\cdot1)-3(1\cdot1-0\cdot2)+1(1\cdot1-2\cdot2)
=-3+(1-4)=-6.
$$

## Final Answer
$$
\det A=6,\qquad \det B=-6.
$$