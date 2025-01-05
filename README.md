# Uncommon CSS `calc()` Gotchas
This repository demonstrates some less common issues that can arise when using the CSS `calc()` function.  Specifically, it highlights unexpected behavior in flexbox contexts and problems stemming from incompatible units within `calc()` expressions.

The `bug.css` file contains code exhibiting these problems. The `bugSolution.css` file shows how to correct these issues.

**Key Issues Addressed:**

* **Flexbox and `calc()`:** The interaction between `calc()` and the flexbox layout model can lead to inconsistent results if not handled carefully.
* **Unit Compatibility:**  Ensure compatibility between different units (e.g., pixels, percentages, ems) within `calc()` expressions to avoid unexpected behavior.
* **Spacing in `calc()` expressions:** Missing spaces around operators in `calc()` is a common cause of parsing errors. 