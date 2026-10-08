# Exercise 2: Different Growth Rates

## Problem Statement
Compute two limits and compare polynomial degrees.

## Theoretical Background and Concepts
For polynomial quotients at infinity: lower numerator degree gives $0$; equal degrees give a leading-coefficient ratio; higher numerator degree often gives unbounded behavior.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\frac{3n+1}{n^2+4}=\frac{3/n+1/n^2}{1+4/n^2}\to0.
$$
$$
\frac{2n^3-n}{5n^2+1}
=n\frac{2-1/n^2}{5+1/n^2}\to+\infty.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The first behaves like $3/n$; the second behaves like $(2/5)n$, confirming both conclusions.
