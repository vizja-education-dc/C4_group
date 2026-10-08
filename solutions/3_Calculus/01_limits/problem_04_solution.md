# Exercise 4: Powers and Oscillation

## Problem Statement
Classify four sequences.

## Theoretical Background and Concepts
For $q^n$, $|q|<1$ gives $0$, $q>1$ grows, and a bounded oscillating factor times a null sequence still tends to $0$.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
(2/3)^n\to0;\qquad (3/2)^n\to+\infty.
$$
$(-1)^n$ alternates between $\pm1$, so it has no limit. Finally,
$$
\frac{(-1)^n}{n}\to0
$$
because its absolute value is $1/n\to0$.

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The squeeze $-1/n\le(-1)^n/n\le1/n$ verifies the final limit.
