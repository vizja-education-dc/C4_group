# Exercise 3: Removing a Radical Indeterminacy

## Problem Statement
Evaluate the limit by conjugation.

## Theoretical Background and Concepts
Multiplying by a conjugate uses $(a-b)(a+b)=a^2-b^2$ to remove cancellation of large radicals.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\sqrt{n^2+5n}-n
=\frac{5n}{\sqrt{n^2+5n}+n}
=\frac5{\sqrt{1+5/n}+1}\to\frac52.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The transformed denominator tends to $2$, so the finite answer is consistent despite both original terms growing without bound.
