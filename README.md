# MongoDB $inc Operator Error

This repository demonstrates an incorrect usage of the `$inc` operator in MongoDB update operations and provides a solution.

The bug involves attempting to increment a field by a string value instead of a number, which results in unexpected behavior.

## Bug Description
The code incorrectly uses a string ('1') as the increment value with the `$inc` operator, leading to an error or unexpected data update.

## Solution
The correct solution uses a number (1) as the increment value.
