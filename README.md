# CSS Calc() Syntax Error Bug

This repository demonstrates a subtle bug related to the CSS `calc()` function.  Incorrect syntax within `calc()` can lead to unexpected styling issues that are difficult to debug.

## Bug Description
A syntax error in the `calc()` function results in the browser ignoring the calculation entirely, potentially leading to unexpected element dimensions or positioning.

## Bug Reproduction
1. Open `bug.css`.
2. Observe the incorrect usage of `calc()` in the `.box` selector.
3. Notice that the width and height of the element are not as expected due to the calculation error.

## Solution
The solution involves reviewing the syntax of the calculation in the `calc()` function and correcting any errors. See `bugSolution.css` for the corrected code.