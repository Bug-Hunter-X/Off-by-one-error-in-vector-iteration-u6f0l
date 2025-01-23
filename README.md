This repository demonstrates a common off-by-one error in C++ when iterating through a std::vector.  The bug.cpp file contains the erroneous code, while bugSolution.cpp provides the corrected version.  The error arises from incorrectly using the <= operator in the loop condition, leading to an out-of-bounds access.  This example highlights the importance of careful loop boundary checks when working with vectors and other dynamic data structures.