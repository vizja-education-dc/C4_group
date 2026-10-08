# Problem 11: Derivative from the Definition

## Problem Statement
Derive the derivative of $x^2$ using only the limit definition.

## Theoretical Background and Concepts
The derivative is the limit of the difference quotient as the increment tends to zero.

### How to Think About This Problem

First identify the outermost operation: sum, product, quotient, or composition. Apply its rule, then work inward one layer at a time. Keep the original domain in view, and after finding $f'$, interpret it: its value is a tangent slope and its sign describes local increase or decrease.

## Detailed Step-by-Step Solution
$$
f'(x)=\lim_{h\to0}\frac{(x+h)^2-x^2}{h}
=\lim_{h\to0}\frac{2xh+h^2}{h}
=\lim_{h\to0}(2x+h)=2x.
$$

## Common Mistakes and Key Takeaway

Common mistakes are differentiating a product as $u'v'$, omitting the inner derivative in the chain rule, or canceling a domain restriction after algebraic simplification. A useful check is to differentiate an equivalent form or test the derivative numerically at a simple point. Always distinguish the derivative formula from the value of the derivative at a point.

## Verification and Consistency Checks
This equals the power-rule result. The limit is used only after canceling $h$, since the original quotient is undefined at $h=0$.
