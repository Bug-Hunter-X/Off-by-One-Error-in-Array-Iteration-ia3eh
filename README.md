# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

The error arises from an incorrect loop condition that attempts to access an array element beyond its bounds, leading to an `ArrayIndexOutOfBoundsException`.

The solution highlights the importance of careful array index handling and demonstrates the correct way to iterate using the `<` operator to stay within the valid index range.