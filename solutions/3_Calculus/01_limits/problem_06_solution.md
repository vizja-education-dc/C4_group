# Exercise 6: Function Limit at Infinity

## Problem Statement
Compute the rational-function limit and compare it with sequence methods.

## Theoretical Background and Concepts
Dominant-degree analysis applies equally to a real variable tending to infinity.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\frac{3x^2-x+1}{5x^2+4x-2}
=\frac{3-1/x+1/x^2}{5+4/x-2/x^2}\to\frac35.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
Only the domain of the argument changes from integers to reals; all reciprocal terms still tend to zero.
