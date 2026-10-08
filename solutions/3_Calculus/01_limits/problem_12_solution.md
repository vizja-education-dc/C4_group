# Exercise 12: Exponential Function Limit

## Problem Statement
Reduce the expression to the classical $e$-limit.

## Theoretical Background and Concepts
$\lim_{u\to0}(1+u)^{1/u}=e$.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
Set $u=3x$. Then $1/x=3/u$, so
$$
(1+3x)^{1/x}=\left((1+u)^{1/u}\right)^3\to e^3.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
Taking logarithms gives $\ln L=\lim \ln(1+3x)/x=3$, hence $L=e^3$.
