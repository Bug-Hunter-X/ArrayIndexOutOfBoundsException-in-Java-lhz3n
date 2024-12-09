# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `Bug.java` file contains code that attempts to access an array element outside the bounds of the array, causing the exception. The `BugSolution.java` file provides a corrected version. 

## How to Reproduce
1. Compile and run `Bug.java`. You should see an `ArrayIndexOutOfBoundsException`.
2. Compile and run `BugSolution.java`.  It correctly handles array access.

## Learning Points
- Always check array indices before accessing elements to prevent `ArrayIndexOutOfBoundsException`.
- Understand that Java arrays are zero-indexed (the first element is at index 0).
- Use appropriate exception handling (try-catch blocks) when working with arrays to gracefully handle potential errors.