# CSS calc() Negative Value Bug

This repository demonstrates a subtle bug that can occur when using the `calc()` function in CSS.  The `calc()` function allows for dynamic calculations, but if the result is a negative value, and the CSS property doesn't support negative values (like `width` or `height`), it can lead to unexpected behavior or rendering issues.

The `bug.css` file contains the problematic CSS. The `solution.css` file shows how to avoid the bug using `max()` or other conditional logic.  Read the comments in each file for more information.