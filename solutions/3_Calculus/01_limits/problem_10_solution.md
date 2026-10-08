# Exercise 10: Continuity of a Piecewise Function

## Problem Statement
Choose $a$ so the function is continuous at $2$.

## Theoretical Background and Concepts
Continuity requires left limit = right limit = function value.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\lim_{x\to2^-}f(x)=2a+1,\qquad
\lim_{x\to2^+}f(x)=f(2)=2^2-1=3.
$$
Thus $2a+1=3$, so
$$
a=1.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
With $a=1$, all three quantities equal $3$.
