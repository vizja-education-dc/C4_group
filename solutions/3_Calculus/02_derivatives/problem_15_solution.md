# Problem 15: Difference Quotient Check

## Problem Statement
Compare exact and numerical difference quotients for one chosen function.

## Theoretical Background and Concepts
The derivative is the limit—not merely several values—of the difference quotient.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
Choose $f(x)=x^2$ and $x_0=1$. Exactly, $f'(1)=2$. Moreover,
$$
\frac{f(1+h)-f(1)}h
=\frac{(1+h)^2-1}{h}=2+h.
$$
For $h=1,0.1,0.01$, the values are $3,2.1,2.01$.

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
These approach $2$, consistent with the derivative. The algebraic limit $\lim_{h\to0}(2+h)=2$ is the proof; the three values alone are only evidence.
