# Problem 4: Quotient and Domain

## Problem Statement
Find the domain and derivative of the rational function.

## Theoretical Background and Concepts
$(u/v)'=(u'v-uv')/v^2$, where $v\ne0$.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
The domain is $\mathbb R\setminus\{1\}$. By the quotient rule,
$$
f'(x)=\frac{2x(x-1)-(x^2+1)}{(x-1)^2}
=\frac{x^2-2x-1}{(x-1)^2}.
$$

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
Polynomial division $f=x+1+2/(x-1)$ differentiates to $1-2/(x-1)^2$, the same expression. The restriction $x\ne1$ remains.
