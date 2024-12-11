This repository demonstrates a potential buffer overflow vulnerability in assembly code and its solution.  The `bug.asm` file contains the vulnerable code, while `bugSolution.asm` provides a corrected version with bounds checking. The vulnerability arises from the use of an array index (ecx) without sufficient validation, leading to potential out-of-bounds memory access.  The solution implements bounds checking before accessing the array to prevent the overflow.