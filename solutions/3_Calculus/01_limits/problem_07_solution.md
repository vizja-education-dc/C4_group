# Exercise 7: Canceling a Factor

## Problem Statement
Compute the limit at $x=3$.

## Theoretical Background and Concepts
A limit concerns nearby values, so algebraic simplification away from the target point is valid.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\frac{x^2-4x+3}{x-3}
=\frac{(x-1)(x-3)}{x-3}=x-1\quad(x\ne3).
$$
Therefore the limit is $3-1=2$.

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The original expression need not be defined at $3$; nearby values equal $x-1$ and approach $2$.
