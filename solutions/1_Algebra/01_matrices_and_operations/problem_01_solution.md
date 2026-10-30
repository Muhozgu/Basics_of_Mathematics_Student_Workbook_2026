# Exercise 1 Solution

## Problem

Given

$$
A=\begin{pmatrix}
2 & -1 & 3 \\
0 & 4 & 5
\end{pmatrix},
\qquad
B=\begin{pmatrix}
1 & 0 \\
-2 & 3 \\
4 & 1
\end{pmatrix}.
$$

1. State the sizes of matrices $A$ and $B$.
2. Find the entries $a_{12}$, $a_{23}$, $b_{21}$, and $b_{32}$.
3. Write the second row of $A$ and the first column of $B$ as vectors.

## Idea

The size of a matrix is the number of rows followed by the number of columns. In $a_{ij}$, the first index $i$ gives the row and the second index $j$ gives the column.

## Solution

### 1. Sizes of the matrices

Matrix $A$ has 2 rows and 3 columns, so its size is $2\times3$.

Matrix $B$ has 3 rows and 2 columns, so its size is $3\times2$.

### 2. Matrix entries

Reading the entries from their indicated row and column positions gives

$$
a_{12}=-1,\qquad a_{23}=5,\qquad b_{21}=-2,\qquad b_{32}=1.
$$

### 3. Row and column vectors

The second row of $A$ is

$$\begin{pmatrix}0 & 4 & 5\end{pmatrix}.$$

The first column of $B$ is

$$
\begin{pmatrix}
1 \\
-2 \\
4
\end{pmatrix}.
$$

## Verification

The indicated entries agree with their positions: $a_{12}$ is in row 1, column 2; $a_{23}$ is in row 2, column 3; $b_{21}$ is in row 2, column 1; and $b_{32}$ is in row 3, column 2. The second row has 3 entries, and the first column has 3 entries.

## Final Answer

$$
\operatorname{size}(A)=2\times3,\qquad \operatorname{size}(B)=3\times2,
$$

$$
a_{12}=-1,\qquad a_{23}=5,\qquad b_{21}=-2,\qquad b_{32}=1,
$$

$$
\text{second row of }A=\begin{pmatrix}0 & 4 & 5\end{pmatrix},
\qquad
\text{first column of }B=
\begin{pmatrix}
1 \\
-2 \\
4
\end{pmatrix}.
$$
