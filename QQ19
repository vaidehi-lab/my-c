#include <stdio.h> 

void printSquare(int size) { // function for printing square pattern
    int i, j;
    for (i = 0; i < size; i++) {
        for (j = 0; j < size; j++) {
            printf("* ");
        }
        printf("\n");
    }
}

void printTriangle(int size) { // fuction for printing triangle pattern
    int i, j;
    for (i = 1; i <= size; i++) {
        for (j = 1; j <= i; j++) {
            printf("* ");
        }
        printf("\n");
    }
}

void printPyramid(int size) { // function for printing pyramid pattern
    int i, j, space;
    for (i = 1; i <= size; i++) {
        for (space = 1; space <= size - i; space++) {
            printf("  "); // Two spaces for alignment
        }
        for (j = 1; j <= 2 * i - 1; j++) {
            printf("* ");
        }
        printf("\n");
    }
}

int main() {
    int choice;  // MENU DRIVEN PROGRAM - for printing different patterns
    int size;
    { 
        printf("\n--- Pattern Printing Menu ---\n");
        printf("1. Print Square\n");
        printf("2. Print Right-Angled Triangle\n");
        printf("3. Print Pyramid\n");
        printf("4. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);

        if (choice >= 1 && choice <= 3) { // Prompt for size only if a pattern is chosen
            printf("Enter the size: ");
            scanf("%d", &size);
        

        switch (choice) {
            case 1:
                printSquare(size);
                break;
            case 2:
                printTriangle(size);
                break;
            case 3:
                printPyramid(size);
                break;
            case 4:
                printf("Exit.\n");
                break;
            default:
                printf("Invalid choice. Please try again.\n");
        }
    }

    return 0;
}
