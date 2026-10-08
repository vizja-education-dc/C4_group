# Exercise 13: Fundamental Trigonometric Limit

## Problem Statement
Reduce two limits to $\sin u/u\to1$.

## Theoretical Background and Concepts
Insert the inner angle in both numerator and denominator to expose the fundamental limit.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\frac{\sin5x}{x}=5\frac{\sin5x}{5x}\to5.
$$
Also,
$$
\frac{\sin2x}{\sin3x}
=\frac{\sin2x}{2x}\frac{3x}{\sin3x}\frac23\to\frac23.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
Each normalized sine ratio tends to $1$, leaving only the displayed constant factor.
