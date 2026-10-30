# Exercise 9 Solution

## Problem
The vectors
$$
u=\begin{pmatrix}3\\1\end{pmatrix},\qquad v=\begin{pmatrix}1\\4\end{pmatrix}
$$
span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

## Solution
The area of the parallelogram spanned by two vectors is the absolute value of the determinant of the matrix formed by those vectors:
$$
\det\begin{pmatrix}3&1\\1&4\end{pmatrix}=3\cdot4-1\cdot1=12-1=11.
$$
So the area is
$$
\boxed{11}.
$$

If the order is reversed, we get
$$
\det\begin{pmatrix}1&3\\4&1\end{pmatrix}=1\cdot1-3\cdot4=1-12=-11.
$$
The determinant changes sign, but the area stays the same:
$$
\text{Area}=|{-11}|=11.
$$

## Final Answer
The parallelogram area is $11$. Reversing the order changes the sign of the determinant but leaves the area unchanged.