# Project Calculus

Sexy simple calculator

Requirements:

1. The calculator can perform addition, subtraction, multiplication and division operations with two numbers: a + b, a - b, a * b, a / b. The data is transferred in one line (see example below). Solutions in which each number and arithmetic operation is passed on a new line are considered incorrect.
2. The calculator can work with both Arabic (1,2,3,4,5...) and Roman (I,II,III,IV,V...) numbers.
3. The calculator must accept numbers from 1 to 10 inclusive as input, no more. The output numbers are not limited in size and can be anything.
4. The calculator can only work with integers.
5. The calculator can only work with Arabic or Roman numerals at a time; when the user enters a string like 3 + II, the calculator should indicate an error and stop working.
6. When entering Roman numerals, the answer should be displayed in Roman numerals, respectively, when entering Arabic numerals, the answer is expected in Arabic.
7. If the user enters inappropriate numbers, the application displays an error in the terminal and exits.
8. If the user enters a string that does not match one of the arithmetic operations described above, the application displays an error and exits.
9. The result of the division operation is an integer, the remainder is discarded.
10. The result of the calculator with Arabic numbers can be negative numbers and zero. The result of a calculator working with Roman numerals can only be positive numbers; if the result of the work is less than one, the program must indicate an exception.

Example of the program:

Input:
1+2

Output:
3

Input:
VI/III

Output:
II

Input:
I - II

Output:
Error output because there are no negative numbers in the Roman system.

Input:
I+1

Output:
Error output because different number systems are used simultaneously.

Input:
1

Output:
Error output because string is not a mathematical operation.

Input:
1 + 2 + 3

Output:
Error output because the format of the mathematical operation does not satisfy the task - two operands and one operator (+, -, /, *).
