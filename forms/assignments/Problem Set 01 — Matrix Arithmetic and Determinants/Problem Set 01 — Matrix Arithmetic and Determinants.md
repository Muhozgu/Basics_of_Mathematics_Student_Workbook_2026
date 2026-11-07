# Problem Set 01 — Matrix Arithmetic and Determinants

## Section A: Matrix operations and basic properties

### Problem 1
Let $A$ be $2 \times 3$, $B$ be $3 \times 2$, and $C$ be $2 \times 2$. State which of $AB$, $BA$, $A + C$, and $AB + C$ are defined, and give their dimensions.

### Problem 2
Calculate $2A - 3B$ for the matrices

$$
A = \begin{pmatrix}
2 & 1 \\
3 & 4
\end{pmatrix},
\qquad
B = \begin{pmatrix}
1 & 2 \\
-2 & 0
\end{pmatrix}.
$$

### Problem 3
For the matrices

$$
A = \begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix},
\qquad
B = \begin{pmatrix}
3 & 0 \\
2 & 1
\end{pmatrix},
$$

find $AB$ and $BA$. Does multiplication commute for this pair?

### Problem 4
Let

$$
A = \begin{pmatrix}
1 & 0 & 2 \\
1 & 3 & 1
\end{pmatrix},
\qquad
B = \begin{pmatrix}
2 & 1 \\
0 & -1 \\
1 & 2
\end{pmatrix}.
$$

Calculate $(AB)^T$ and verify that

$$
(AB)^T = B^T A^T.
$$

### Problem 5
Classify the matrices

$$
D = \begin{pmatrix}
3 & 0 \\
0 & 3
\end{pmatrix},
\qquad
S = \begin{pmatrix}
1 & -2 \\
-2 & 5
\end{pmatrix},
\qquad
K = \begin{pmatrix}
0 & 4 \\
-4 & 0
\end{pmatrix}.
$$

Identify diagonal, scalar, symmetric, and skew-symmetric matrices; more than one label may apply.

Also classify

$$
T = \begin{pmatrix}
2 & 1 \\
0 & 3
\end{pmatrix},
\qquad
I_2,
\qquad
0_{2\times 3}
$$
as triangular, identity, or zero matrices, stating their dimensions.

---

## Section B: Determinants and singularity

### Problem 6
For which real values of $t$ is the matrix

$$
A(t) = \begin{pmatrix}
t & 2 \\
3 & t-1
\end{pmatrix}
$$

singular?

### Problem 7
Calculate

$$
\det\begin{pmatrix}
2 & 1 & 0 \\
-1 & 3 & 2 \\
1 & 0 & 4
\end{pmatrix}
$$

using Sarrus' rule. State why this rule is applicable.

### Problem 8
For the matrix

$$
A = \begin{pmatrix}
2 & 1 & 0 \\
-1 & 3 & 2 \\
1 & 0 & 4
\end{pmatrix},
$$

find the minor $M_{23}$ and cofactor $C_{23}$. Explain their sign difference.

### Problem 9
Calculate

$$
\det\begin{pmatrix}
0 & 2 & 0 \\
1 & -1 & 3 \\
4 & 0 & 2
\end{pmatrix}
$$

by Laplace expansion along the first row. Check the result by expanding down the first column.

### Problem 10
Let $A$ and $B$ be $3\times 3$ matrices with $\det(A)=2$ and $\det(B)=5$. Find $\det(AB)$ and $\det(2A^T)$.

A matrix $C$ is formed from $A$ by swapping two rows and then multiplying one row by $3$; find $\det(C)$.

---

This document is a cleaned, LaTeX-ready version of the original problem set, arranged in a more polished textbook style for reading and printing.
