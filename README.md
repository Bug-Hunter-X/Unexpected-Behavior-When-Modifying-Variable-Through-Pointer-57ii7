# Unexpected Behavior When Modifying Variable Through Pointer

This repository demonstrates a subtle bug in C related to pointer arithmetic and unexpected behavior when modifying a variable through a pointer.  The code appears straightforward but may exhibit unexpected behavior due to compiler optimizations or issues with pointer arithmetic, especially in more complex scenarios.

The `bug.c` file contains the buggy code, while `bugSolution.c` offers a potential solution and explanation.

**Bug Description:**
The issue lies in modifying the value of an integer variable indirectly via a pointer. While generally correct, subtle issues can arise in certain contexts.

**Solution:**
The provided solution in `bugSolution.c` maintains clarity and avoids potential unexpected behaviors.

This simple example highlights the importance of understanding pointer behavior and the potential for unexpected consequences.