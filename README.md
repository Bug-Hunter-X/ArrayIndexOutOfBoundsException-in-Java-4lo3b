# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`.  The bug is caused by incorrect loop indexing when iterating over an array.  The solution corrects the loop condition to prevent the exception.

## Bug Description

The provided Java code attempts to access an element outside the valid index range of an array. This leads to an `ArrayIndexOutOfBoundsException` being thrown at runtime.  The error is subtle and commonly occurs for programmers new to Java arrays.

## Solution

The `BugSolution.java` file offers a corrected version of the code, featuring the correct loop condition to avoid the index-out-of-bounds exception. By changing the loop's termination condition from `i <= arr.length` to `i < arr.length`, the bug is rectified. This ensures that the loop only iterates within the valid index range of the array.