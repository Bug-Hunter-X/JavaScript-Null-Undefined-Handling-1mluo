# JavaScript Null/Undefined Handling Bug

This repository demonstrates a common error in JavaScript related to handling `null` and `undefined` values. The `bug.js` file shows the buggy code, and `bugSolution.js` provides a corrected version.

## Bug Description

The original code does not explicitly handle cases where function arguments (`a` and `b`) might be `null` or `undefined`. This can lead to unexpected behavior, particularly if the code performs operations (like addition) that are not defined for `null` or `undefined`.

## Solution

The solution adds explicit checks for `null` or `undefined` values before performing the addition.  This prevents errors and ensures the function behaves correctly in all scenarios.  The corrected code returns 0 if either argument is `null` or `undefined`.