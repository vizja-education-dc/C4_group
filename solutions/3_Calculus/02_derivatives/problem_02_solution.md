# Problem 2: Powers, Roots, and Domain

## Problem Statement
Rewrite, find the domain, differentiate, and compare domains.

## Theoretical Background and Concepts
Rewrite radicals and reciprocals as powers before applying the power rule.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
$$
f(x)=2x^{1/2}-3x^{-2}+x^{3/2}.
$$
The square root requires $x\ge0$, while $x^{-2}$ excludes $0$, so $\operatorname{dom}f=(0,\infty)$. Then
$$
f'(x)=x^{-1/2}+6x^{-3}+\frac32x^{1/2}.
$$

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
The derivative has the same domain $(0,\infty)$; its negative powers also exclude $0$.
