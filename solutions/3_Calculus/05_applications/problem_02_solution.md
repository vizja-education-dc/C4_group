# Problem 2: Maximum Rectangle Area

## Problem Statement
Model and maximize the area of a rectangle with perimeter $40$.

## Theoretical Background and Concepts
Use the constraint to reduce two dimensions to one variable, then test the critical point.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
Let the sides be $x,y>0$. From $2x+2y=40$, $y=20-x$, with $0<x<20$. Hence
$$
A(x)=x(20-x)=20x-x^2.
$$
$A'(x)=20-2x=0$ gives $x=10$, hence $y=10$ and maximum area $100$.

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
$A''=-2<0$, so the critical point is a strict maximum; also $A\to0$ at both domain endpoints.
