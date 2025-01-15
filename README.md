# CSS `calc()` Gotchas

This repository demonstrates potential pitfalls when using the CSS `calc()` function, specifically regarding operator precedence and unit consistency.  The `bug.css` file shows examples of code that can lead to unexpected behavior, and the `bugSolution.css` file offers solutions and best practices.

## Issues

* **Operator Precedence:** The order of operations in `calc()` might not always be intuitive, leading to incorrect calculations if not carefully parenthesized.
* **Inconsistent Units:** Mixing units (e.g., pixels and percentages) without proper consideration can lead to unexpected results.

## Solutions

* Always use parentheses `()` to explicitly define the order of operations in complex `calc()` expressions.
* Ensure consistent units within a single `calc()` expression for accurate calculations.
* Thoroughly test your CSS to account for potential edge cases and browser inconsistencies.