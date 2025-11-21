#include <stdio.h>

int main() {
    int choice;
    int side1, side2, side3;

    printf("--- Triangle Type Checker ---\n"); // MENU DRIVEN PROGRAM- for checking triangle type
    printf("1. Check Triangle Type\n");
    printf("2. Exit\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    switch (choice) {
        case 1:
            printf("Enter the lengths of three sides:",&side1,&side2,&side3)
            // Basic check for valid triangle sides (triangle inequality theorem)
            if (side1 + side2 > side3 && side1 + side3 > side2 && side2 + side3 > side1) {
                if (side1 == side2 && side2 == side3) 
                    printf("The triangle is Equilateral.\n");
                else if (side1 == side2 || side2 == side3 || side1 == side3) 
                    printf("The triangle is Isosceles.\n");
                else 
                    printf("The triangle is Scalene.\n");
            }
            else 
                printf("Invalid triangle sides. The sum of any two sides must be greater than the third side.\n");
            break;
        case 2:
            printf("Exit!\n");
            break;
        default:
            printf("Invalid choice. Please enter 1 or 2.\n");
            break;
    }
  return 0;
}
