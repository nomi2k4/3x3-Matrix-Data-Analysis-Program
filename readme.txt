3x3 Matrix Data Analysis Program
A simple C++ program that performs various data analysis operations on a predefined 3x3 matrix.

Overview
This program defines a struct testData to represent a 3x3 matrix. It then provides functions to calculate the total, average, row totals, column totals, and highest values in rows and columns.

Features
- Calculates total of all elements in the matrix
- Calculates average of all elements in the matrix
- Calculates total of elements in a specified row
- Calculates total of elements in a specified column
- Finds highest value in a specified row
- Finds highest value in a specified column

Requirements
- C++ compiler (e.g., GCC)
- Standard C++ libraries (e.g., iostream)

Usage
1. Compile the program using a C++ compiler (e.g., g++ matrix_analysis.cpp -o matrix_analysis)
2. Run the program (e.g., ./matrix_analysis)

Notes
- This program uses a predefined 3x3 matrix. For larger matrices, consider using dynamic memory allocation or a container class like std::vector.
- Error handling is minimal in this program. Consider adding checks for invalid user input or other potential errors.