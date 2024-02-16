# Manish-cppfile
//This file has the c++ code to find the determinant of a matrix
#include<iostream>

using namespace std;

int main() {
    // Define a 2x2 matrix
    int matrix[2][2];

    // Input elements of the matrix
    cout << "Enter the elements of the 2x2 matrix:" << endl;
    for(int i = 0; i < 2; ++i) {
        for(int j = 0; j < 2; ++j) {
            cin >> matrix[i][j];
        }
    }

    // Calculate the determinant
    int determinant = matrix[0][0] * matrix[1][1] - matrix[0][1] * matrix[1][0];

    // Display the determinant
    cout << "Determinant of the matrix: " << determinant << endl;

    return 0;
}

