# Problem 12: Several Rules at Once

## Problem Statement
Plan and differentiate a product containing a composition.

## Theoretical Background and Concepts
Apply the product rule to the whole expression and the chain rule to $(x^2+1)^3$.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
$$
f'=6x(x^2+1)^2e^x+(x^2+1)^3e^x.
$$
Factoring gives
$$
f'(x)=e^x(x^2+1)^2(x^2+6x+1).
$$

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
Expanding the factored result recreates the two product-rule terms.
