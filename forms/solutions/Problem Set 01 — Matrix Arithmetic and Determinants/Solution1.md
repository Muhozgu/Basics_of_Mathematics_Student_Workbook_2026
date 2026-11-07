# Solution 1

For a product $XY$ to be defined, the number of columns of $X$ must equal
the number of rows of $Y$. The product then has the same number of rows as
$X$ and the same number of columns as $Y$. Matrix addition is defined only
when the matrices have the same dimensions.

Here, $A$ is $2 \times 3$, $B$ is $3 \times 2$, and $C$ is $2 \times 2$.

| Expression | Defined? | Reason and dimensions |
|---|---|---|
| $AB$ | Yes | The inner dimensions agree ($3 = 3$), so $AB$ is $2 \times 2$. |
| $BA$ | Yes | The inner dimensions agree ($2 = 2$), so $BA$ is $3 \times 3$. |
| $A + C$ | No | $A$ is $2 \times 3$, whereas $C$ is $2 \times 2$; their dimensions differ. |
| $AB + C$ | Yes | Both $AB$ and $C$ are $2 \times 2$, so their sum is $2 \times 2$. |

Therefore, $AB$, $BA$, and $AB+C$ are defined, while $A+C$ is not.