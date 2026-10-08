# Problem 14: Continuity and Differentiability

## Problem Statement
Classify continuity and differentiability at $0$ by $a$.

## Theoretical Background and Concepts
Differentiability requires continuity plus equal finite one-sided derivatives.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
Both branches approach $0=f(0)$, so the function is continuous for every $a$. The left derivative at $0$ is
$$
\lim_{h\to0^-}\frac{ah-0}{h}=a,
$$
while the right derivative is
$$
\lim_{h\to0^+}\frac{h^2}{h}=0.
$$
They agree exactly when $a=0$; only then is $f$ differentiable.

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
For $a\ne0$, the graph joins continuously but has unequal left and right slopes, showing why continuity is insufficient.
