#include <stdio.h>
// Function to read matrix elements
void readMatrix(int rows, int cols, int matrix[10][10]) {
    int i, j;
    printf("Enter elements of the matrix:\n");
    for (i = 0; i < rows; i++) {
        for (j = 0; j < cols; j++) {
            printf("Enter element [%d][%d]: ", i, j);
            scanf("%d", &matrix[i][j]);
        }
    }
}
// Function to print matrix elements
void printMatrix(int rows, int cols, int matrix[10][10]) {
    int i, j;
    printf("Matrix:\n");
    for (i = 0; i < rows; i++) {
        for (j = 0; j < cols; j++) {
            printf("%d\t", matrix[i][j]);
        }
        printf("\n");
    }
}
// Function for matrix addition
void addMatrices(int rows, int cols, int matrix1[10][10], int matrix2[10][10], int result[10][10]) {
    int i, j;
    for (i = 0; i < rows; i++) {
        for (j = 0; j < cols; j++) {
            result[i][j] = matrix1[i][j] + matrix2[i][j];
        }
    }
}
// Function for matrix subtraction
void subtractMatrices(int rows, int cols, int matrix1[10][10], int matrix2[10][10], int result[10][10]) {
    int i, j;
    for (i = 0; i < rows; i++) {
        for (j = 0; j < cols; j++) {
            result[i][j] = matrix1[i][j] - matrix2[i][j];
        }
    }
}
int main() { // MENU DRIVEN PROGRAM - for matrix operations
    int choice;
    int rows1, cols1, rows2, cols2;
    int matrix1[10][10], matrix2[10][10], resultMatrix[10][10];

    do {
        printf("\n--- Matrix Operations Menu ---\n");
        printf("1. Matrix Addition\n");
        printf("2. Matrix Subtraction\n");
        printf("3. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);

        switch (choice) {
            case 1:
                printf("Enter dimensions for Matrix 1 (rows cols): ");
                scanf("%d %d", &rows1, &cols1);
                readMatrix(rows1, cols1, matrix1);

                printf("Enter dimensions for Matrix 2 (rows cols): ");
                scanf("%d %d", &rows2, &cols2);
                readMatrix(rows2, cols2, matrix2);

                if (rows1 == rows2 && cols1 == cols2) {
                    addMatrices(rows1, cols1, matrix1, matrix2, resultMatrix);
                    printf("\nResult of Matrix Addition:\n");
                    printMatrix(rows1, cols1, resultMatrix);
                } else {
                    printf("Matrices must have the same dimensions for addition.\n");
                }
                break;

            case 2:
                printf("Enter dimensions for Matrix 1 (rows cols): ");
                scanf("%d %d", &rows1, &cols1);
                readMatrix(rows1, cols1, matrix1);

                printf("Enter dimensions for Matrix 2 (rows cols): ");
                scanf("%d %d", &rows2, &cols2);
                readMatrix(rows2, cols2, matrix2);

                if (rows1 == rows2 && cols1 == cols2) {
                    subtractMatrices(rows1, cols1, matrix1, matrix2, resultMatrix);
                    printf("\nResult of Matrix Subtraction:\n");
                    printMatrix(rows1, cols1, resultMatrix);
                } else {
                    printf("Matrices must have the same dimensions for subtraction.\n");
                }
                break;

            case 3:
                printf("Exiting program.\n");
                break;

            default:
                printf("Invalid choice. Please try again.\n");
        }
    } while (choice != 3);

    return 0;
}
