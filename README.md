# Off-by-one Error in Array Iteration
This example demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs because the loop condition `i <= array.length` attempts to access an index beyond the valid range of the array, causing an `ArrayIndexOutOfBoundsException`.

The solution involves correcting the loop condition to `i < array.length` to ensure that the loop iterates only within the bounds of the array.