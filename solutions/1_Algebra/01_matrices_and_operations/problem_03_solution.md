# Exercise 3 Solution

## Problem

The matrix sizes are

$$
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.
$$

Determine whether each of $AB$, $BA$, $BC$, $CB$, $AC$, $CA$, $AD$, and $DA$ is defined. For every defined product, state its size.

## Idea

If the first matrix has size $m\times n$ and the second has size $p\times q$, their product is defined only when $n=p$. When it is defined, the product has size $m\times q$.

## Solution

| Product | Dimension check | Defined? | Result size |
|---|---|---|---|
| $AB$ | $(2\times3)(3\times4)$ | Yes | $2\times4$ |
| $BA$ | $(3\times4)(2\times3)$ | No: $4\ne2$ | — |
| $BC$ | $(3\times4)(4\times2)$ | Yes | $3\times2$ |
| $CB$ | $(4\times2)(3\times4)$ | No: $2\ne3$ | — |
| $AC$ | $(2\times3)(4\times2)$ | No: $3\ne4$ | — |
| $CA$ | $(4\times2)(2\times3)$ | Yes | $4\times3$ |
| $AD$ | $(2\times3)(2\times2)$ | No: $3\ne2$ | — |
| $DA$ | $(2\times2)(2\times3)$ | Yes | $2\times3$ |

## Verification

In every defined product, the inner dimensions agree. Its result uses the outer dimensions. Every product marked undefined has unequal inner dimensions.

## Final Answer

The defined products and their sizes are

$$
AB:2\times4,\qquad BC:3\times2,\qquad CA:4\times3,\qquad DA:2\times3.
$$

The products $BA$, $CB$, $AC$, and $AD$ are undefined.
