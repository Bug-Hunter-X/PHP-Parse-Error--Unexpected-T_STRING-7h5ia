# PHP Parse Error: Unexpected T_STRING

This repository demonstrates a subtle PHP bug that can occur when accidentally omitting parentheses when calling a function.  The error is not immediately obvious and can be tricky to debug.

The `bug.php` file contains the erroneous code, while `bugSolution.php` provides the corrected version.

**Key takeaway**: Always use parentheses when calling functions in PHP to avoid unexpected parse errors.