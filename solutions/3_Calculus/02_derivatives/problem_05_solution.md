# Problem 5: Chain Rule

## Problem Statement
Identify layers and differentiate the fifth power.

## Theoretical Background and Concepts
For $f=g\circ h$, $f'=g'(h)h'$; the extra factor comes from the inner rate of change.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
Let $h(x)=3x^2-2x+1$ and $g(u)=u^5$. Then $h'=6x-2$, $g'=5u^4$, so
$$
f'(x)=5(3x^2-2x+1)^4(6x-2).
$$

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
The factor $6x-2$ is exactly the derivative of the inner expression, as required by the chain rule.
