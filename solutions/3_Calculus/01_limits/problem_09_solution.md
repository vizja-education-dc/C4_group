# Exercise 9: One-Sided Limits

## Problem Statement
Analyze $1/(x-2)$ at $x=2$.

## Theoretical Background and Concepts
Opposite infinite one-sided limits prevent a two-sided limit and indicate a vertical asymptote.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
As $x\to2^-$, $x-2$ is negative and approaches $0$, so
$$
\lim_{x\to2^-}\frac1{x-2}=-\infty.
$$
As $x\to2^+$, it is positive, so the limit is $+\infty$. The two-sided limit does not exist, and $x=2$ is a vertical asymptote.

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The graph has a left branch falling without bound and a right branch rising without bound, matching the signs.
