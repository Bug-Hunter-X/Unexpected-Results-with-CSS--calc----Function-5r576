# Unexpected Results with CSS `calc()` Function

This repository demonstrates an uncommon bug related to the CSS `calc()` function.  The `calc()` function is powerful, but requires careful attention to detail.  Incorrect usage can lead to unexpected layout issues.

The `bug.css` file contains the problematic code. The `bugSolution.css` file provides the corrected version, showing how to avoid this specific bug.

**Problem:** The `calc()` function doesn't always work as expected if the parent element's size is not explicitly defined. 

**Solution:** Ensure the parent element has defined dimensions (e.g., using `width` or `height`) to provide the correct context for `calc()` calculations.