# Problem 8: Server Requests

## Problem Statement
Compute total requests and average arrival rate over five minutes.

## Theoretical Background and Concepts
Integrating a rate gives accumulated quantity; average rate is total divided by elapsed time.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
$$
\int_0^5(100+20t)dt
=\left[100t+10t^2\right]_0^5=750
$$
requests. The average rate is $750/5=150$ requests/min.

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
$r(0)=100$ and $r(5)=200$; the average $150$ lies midway between them, as expected for a linear rate.
