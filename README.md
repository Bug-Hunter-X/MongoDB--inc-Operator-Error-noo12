# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value, but attempting to increment with a string value will result in an error.

## Bug
The bug lies in the incorrect usage of the `$inc` operator, where a string value ("1") is provided instead of a number (1).

## Solution
The solution involves correcting the update operation to provide a numerical value to the `$inc` operator.