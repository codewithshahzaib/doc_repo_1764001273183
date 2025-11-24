# Core Arithmetic Operations

At the heart of the calculator are the primary arithmetic operations: addition, subtraction, multiplication, and division. These functions are implemented with attention to precision and error handling, ensuring accurate results even under high frequency usage. Division operations include built-in safeguards against division by zero, providing user-friendly error messages rather than system failures. The implementation aligns with ITIL principles by ensuring reliable service delivery with minimal downtime. These essentials form the backbone of the calculator's functional offering, meeting the foundational needs of the user base.

### 2.1 Addition
The addition function supports integer and floating-point numbers, handling edge cases such as overflow with appropriate exceptions. Optimized algorithms ensure that large series of additions are computed efficiently, and unit tests cover various scenarios to maintain robustness.

### 2.2 Subtraction
Subtraction operations consider precision loss in floating-point arithmetic and apply corrective measures. The function gracefully handles inputs that could result in negative values, depending on the calculation context.

### 2.3 Multiplication
Multiplication is implemented to maintain performance even with large operands and includes checks for arithmetic overflow. The function also supports chained multiplication operations with consistent accuracy.
