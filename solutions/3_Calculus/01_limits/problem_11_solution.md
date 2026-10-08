# Exercise 11: An $n$-th Root

## Problem Statement
Evaluate $\sqrt[n]{5^n+2^n}$ by identifying the dominant term.

## Theoretical Background and Concepts
Factor out the largest exponential base before taking an $n$-th root.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\sqrt[n]{5^n+2^n}
=5\left(1+\left(\frac25\right)^n\right)^{1/n}\to5\cdot1=5.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
$$
5\le\sqrt[n]{5^n+2^n}\le5\sqrt[n]{2},
$$
and both bounds tend to $5$, confirming the answer by squeezing.
