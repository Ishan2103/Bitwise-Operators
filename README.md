AIM -
To perform bitwise operations and set reset

Software Used
VS Code

Theory
Expriment 4(a)
Bitwise operators are used to perform operations on the binary representations of integers. They operate at the bit level and are fundamental for tasks that require efficient data manipulation, such as low-level programming, cryptography, and performance optimization. Bitwise operations are faster than arithmetic operations and can be used to implement various algorithms and data structures.

Types of Bitwise Operators
Bitwise operators include:

Bitwise AND (&) : Performs a bitwise AND operation between two integers. The result is an integer where each bit is set to 1 if the corresponding bits of both operands are 1; otherwise, it is 0. Example: 5 & 3 (binary: 0101 & 0011) results in 1 (binary: 0001).

Bitwise OR (|) : Performs a bitwise OR operation between two integers. The result is an integer where each bit is set to 1 if at least one of the corresponding bits of the operands is 1. Example: 5 | 3 (binary: 0101 | 0011) results in 7 (binary: 0111).

Bitwise XOR (^) : Performs a bitwise XOR (exclusive OR) operation between two integers. The result is an integer where each bit is set to 1 if the corresponding bits of the operands are different; otherwise, it is 0. Example: 5 ^ 3 (binary: 0101 ^ 0011) results in 6 (binary: 0110).

Bitwise NOT (~) : Performs a bitwise NOT (complement) operation on an integer. The result is an integer where each bit is inverted (i.e., 0 becomes 1, and 1 becomes 0). Example: ~5 (binary: ~0101) results in -6 (binary: ...1010 in two's complement representation).

Left Shift (<<) : Shifts the bits of an integer to the left by a specified number of positions. Zeros are shifted into the rightmost bits. This operation effectively multiplies the integer by 2 for each shift position. Example: 5 << 1 (binary: 0101 << 1) results in 10 (binary: 1010).

Right Shift (>>) : Shifts the bits of an integer to the right by a specified number of positions. The behavior for the leftmost bits depends on the sign of the integer (logical shift for unsigned integers, arithmetic shift for signed integers). This operation effectively divides the integer by 2 for each shift position. Example: 5 >> 1 (binary: 0101 >> 1) results in 2 (binary: 0010).

Expriment 4(b)
Binary Setting-
Setting a bit means altering the bit at a specific position to 1 while keeping other bits unchanged. This operation is useful in scenarios where specific flags or bits need to be activated.

Binary Setting-
Resetting a bit involves changing the bit at a specific position to 0 while keeping other bits unchanged. This operation is commonly used to deactivate specific flags or bits.
