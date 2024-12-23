# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java error: the ArrayIndexOutOfBoundsException. The `Bug.java` file contains the erroneous code, which attempts to access an array element outside its valid index range. The `BugSolution.java` file provides a corrected version.

## How to reproduce
1. Clone this repository.
2. Compile `Bug.java` using a Java compiler (e.g., `javac Bug.java`).
3. Run the compiled code (e.g., `java Bug`).  Observe the `ArrayIndexOutOfBoundsException`. 
4. Compile and run `BugSolution.java` to see the corrected behavior. 

## Solution
The solution involves checking the array index before accessing the element to ensure it is within the valid range (0 to array.length -1).