#include <stdio.h>
#include <math.h> 
int main() {
    int choice; // MENU DRIVEN PROGRAM for Area of cirle,rectangle and triangle.
    float area;

    printf("Menu Driven Program: Calculate Area\n");
    printf("----------------------------------\n");
    printf("1. Area of Circle\n");
    printf("2. Area of Rectangle\n");
    printf("3. Area of Triangle\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    switch (choice) { //Area of Circle
        case 1: {
            float radius;
            printf("Enter the radius of the circle: ");
            scanf("%f", &radius);
            area = M_PI * radius * radius; // M_PI is from math.h for pi
            printf("Area of the circle: %.2f\n", area);
            break;
        }
        case 2: { // Area of Rectangle
            float length, width;
            printf("Enter the length of the rectangle: ");
            scanf("%f", &length);
            printf("Enter the width of the rectangle: ");
            scanf("%f", &width);
            area = length * width;
            printf("Area of the rectangle: %.2f\n", area);
            break;
        }
        case 3: { // Area of Triangle (using base and height)
            float base, height;
            printf("Enter the base of the triangle: ");
            scanf("%f", &base);
            printf("Enter the height of the triangle: ");
            scanf("%f", &height);
            area = 0.5 * base * height;
            printf("Area of the triangle: %.2f\n", area);
            break;
        }
        default: {
            printf("Invalid choice. Please enter a number between 1 and 3.\n");
            break;
        }
    }

    return 0;
}
