# Exercise 8 Solution

## Problem

Starting with

$$
A=\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3
\end{pmatrix},
$$

perform these row operations in order:

1. $R_2\leftarrow R_2-2R_1$
2. $R_3\leftarrow R_3+R_1$
3. Interchange $R_2$ and $R_3$

Write the matrix after each operation and state how to reverse each operation.

## Solution

### 1. Apply $R_2\leftarrow R_2-2R_1$

The new second row is

$$
(2,4,1)-2(1,2,-1)=(0,0,3).
$$

Thus the matrix becomes

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
-1 & 1 & 3
\end{pmatrix}.
$$

The inverse operation is $R_2\leftarrow R_2+2R_1$.

### 2. Apply $R_3\leftarrow R_3+R_1$

Using the current first and third rows, the new third row is

$$
(-1,1,3)+(1,2,-1)=(0,3,2).
$$

The matrix becomes

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
0 & 3 & 2
\end{pmatrix}.
$$

The inverse operation is $R_3\leftarrow R_3-R_1$.

### 3. Interchange $R_2$ and $R_3$

The resulting matrix is

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 2 \\
0 & 0 & 3
\end{pmatrix}.
$$

The inverse operation is to interchange $R_2$ and $R_3$ again.

## Verification

Each operation changes only the specified row or rows. Reversing the operations in reverse order restores the original matrix.

## Final Answer

The matrices after steps 1, 2, and 3 are respectively

$$
\begin{pmatrix}1&2&-1\\0&0&3\\-1&1&3\end{pmatrix},
\qquad
\begin{pmatrix}1&2&-1\\0&0&3\\0&3&2\end{pmatrix},
\qquad
\begin{pmatrix}1&2&-1\\0&3&2\\0&0&3\end{pmatrix}.
$$

The inverse operations are, respectively,
$R_2\leftarrow R_2+2R_1$,
$R_3\leftarrow R_3-R_1$,
and interchange $R_2$ and $R_3$ again.
