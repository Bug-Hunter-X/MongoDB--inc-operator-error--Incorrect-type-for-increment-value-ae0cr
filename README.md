This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value. However, an error occurs if you try to increment using a non-numeric value (such as a string). This example shows the error and provides a solution to correct it.  Please refer to the `bug.js` and `bugSolution.js` files for code examples.