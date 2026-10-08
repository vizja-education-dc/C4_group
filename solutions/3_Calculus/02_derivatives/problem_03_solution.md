# Problem 3: Product Rule

## Problem Statement
Differentiate the product and diagnose the proposed incorrect result.

## Theoretical Background and Concepts
$(uv)'=u'v+uv'$: both varying factors contribute.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
$$
f'(x)=2xe^x+(x^2+1)e^x=e^x(x^2+2x+1).
$$
The proposed $2xe^x$ includes only $u'v$ and omits $uv'=(x^2+1)e^x$.

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
At $x=0$, the correct derivative is $1$, whereas the incomplete expression gives $0$, exposing the missing term.
