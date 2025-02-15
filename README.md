# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The code attempts to access an array element beyond its bounds, resulting in an `ArrayIndexOutOfBoundsException`. The solution shows the corrected code with proper loop bounds.

## Bug

The `bug.java` file contains the buggy code. The loop condition `i <= arr.length` is incorrect, causing an out-of-bounds access.

## Solution

The `bugSolution.java` file provides the corrected code. The loop condition is changed to `i < arr.length` to avoid the off-by-one error.