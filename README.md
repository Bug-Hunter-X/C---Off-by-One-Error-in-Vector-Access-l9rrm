# C++ Off-by-One Error Example
This repository demonstrates a common off-by-one error in C++ when accessing elements of a `std::vector`.  The error occurs because the loop condition `i <= 10` attempts to access an element beyond the vector's bounds. 

**bug.cpp** contains the code with the error.

**bugSolution.cpp** provides the corrected code with the explanation of the bug fix.