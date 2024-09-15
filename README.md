matrix-vector-multiplication-openmp
This project demonstrates parallel matrix-vector multiplication using OpenMP in C.

Prerequisites
OpenMP: Make sure your compiler supports OpenMP (e.g., GCC).
GCC: Install GCC if it's not already installed. On Ubuntu, you can use sudo apt-get install gcc.
Setup
Clone the repository:
git clone https://github.com/yourusername/matrix-vector-multiplication-openmp.git
cd matrix-vector-multiplication-openmp
Develop the Code
Create a C File: In your project directory (i.e.matrix-vector-multiplication-openmp), create a file named matrix_vector_multiplication.c.
Write the Code: Use the following C code to perform matrix-vector multiplication in parallel with OpenMP
Compile the code using GCC with OpenMP support in terminal
gcc -o matrix_vector_multiplication matrix_vector_multiplication.c -fopenmp

Execute the compiled program
./matrix_vector_multiplication

Explanation
matrix_vector_multiplication: Function that multiplies a matrix by a vector in parallel.
OpenMP Parallel For: Used to parallelize the for loop to compute the matrix-vector product.
