# MongoDB $inc Operator Type Error

This example demonstrates an uncommon error in MongoDB that can occur when using the `$inc` operator to increment a numerical field. The error arises from providing a string value instead of a numerical value to the `$inc` operator.

## Bug

The `bug.js` file contains a MongoDB update operation that uses the `$inc` operator to increment the `age` field of a document. However, instead of providing a numerical value, it provides a string value which is incorrect and throws an error.

## Solution

The `bugSolution.js` file corrects the error by providing a numerical value to the `$inc` operator, ensuring that the `age` field is incremented correctly.
