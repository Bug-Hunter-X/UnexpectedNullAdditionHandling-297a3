# Unexpected Null Handling in Addition Function

This repository demonstrates a common JavaScript error related to unexpected null handling. The `foo` function is designed to add two numbers. However, it returns `null` if either of the inputs is `null`. This behavior might not always be desired and can lead to unexpected results.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file presents a corrected version of the function that handles null values more appropriately.

## Bug
The `foo` function immediately returns `null` if either input `a` or `b` is `null`, preventing the addition operation.  This is unexpected behavior in many scenarios where a default value might be more suitable.

## Solution
The solution provided in `bugSolution.js` checks for null values and uses 0 as a default value if either `a` or `b` is null. This ensures the function always attempts the addition, providing a more robust solution.