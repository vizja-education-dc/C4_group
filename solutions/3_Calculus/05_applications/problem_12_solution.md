# Problem 12: Exhibition Room Optimization

## Problem Statement
Model and maximize area under the unequal-cost budget constraint, then verify numerically.

## Theoretical Background and Concepts
Separate modeling (variables, costs, domain) from one-variable optimization by differentiation.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
Let $x$ meters be each side perpendicular to the wall and $y$ meters the constructed side parallel to it. The budget gives
$$
2(300)x+500y=30000,
\qquad y=60-1.2x.
$$
The physical domain is $0<x<50$, and
$$
A(x)=xy=60x-1.2x^2.
$$
Then $A'(x)=60-2.4x=0$ at $x=25$, and $A''=-2.4<0$. Thus
$$
x=25\text{ m},\qquad y=30\text{ m},\qquad A_{\max}=750\text{ m}^2.
$$
The graph is a downward-opening parabola with zeros $0,50$ and vertex $(25,750)$.

Numerical verification:

| $x$ (m) | 24 | 24.5 | 25 | 25.5 | 26 |
|---:|---:|---:|---:|---:|---:|
| $A(x)$ (m²) | 748.8 | 749.7 | 750.0 | 749.7 | 748.8 |

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
$600(25)+500(30)=30000$ PLN, so the optimum respects the budget. Defining the variables and cost equation was the modeling step; differentiation and evaluation were calculation, with the table serving only as verification.
