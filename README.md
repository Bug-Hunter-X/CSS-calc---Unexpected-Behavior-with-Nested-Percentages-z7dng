# CSS calc() Issue with Nested Percentages

This repository demonstrates a subtle bug related to the `calc()` function in CSS when used with percentage values within nested elements.  The expected behavior of `calc(100% - 20px)` is not consistent across all browsers when the parent element also uses percentages for its width.

The `bug.css` file showcases the problematic CSS. The `bugSolution.css` file provides a potential solution or workaround, demonstrating how to achieve the desired outcome.