# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical field.  However, if you provide a non-numeric value (like a string), it will result in an error or unexpected behavior.

## Bug
The `bug.js` file contains code with the incorrect usage of `$inc`, providing a string instead of a number. This will cause MongoDB to throw an error.

## Solution
The `bugSolution.js` file provides the corrected code with the correct numeric value for the `$inc` operator.