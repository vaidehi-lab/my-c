#include <stdio.h>

int main() {
    int choice;
    double value, result;
        printf("\nUnit Conversion Program\n");  // MENU DRIVEN PROGRAM  - for Unit conversion 
        printf("---------------------\n");
        printf("1. Kilometers to Meters\n");
        printf("2. Meters to Kilometers\n");
        printf("3. Meters to Centimeters\n");
        printf("4. Centimeters to Meters\n");
        printf("5. Kilometers to Centimeters\n");
        printf("6. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &choice);
        switch (choice) {
            case 1:
                printf("Enter distance in kilometers (km): ");
                scanf("%lf", &value);
                result = value * 1000.0;
                printf("%.2lf km is equal to %.2lf meters.\n", value, result);
                break;
            case 2:
                printf("Enter distance in meters (m): ");
                scanf("%lf", &value);
                result = value / 1000.0;
                printf("%.2lf m is equal to %.2lf kilometers.\n", value, result);
                break;
            case 3:
                printf("Enter distance in meters (m): ");
                scanf("%lf", &value);
                result = value * 100.0;
                printf("%.2lf m is equal to %.2lf centimeters.\n", value, result);
                break;
            case 4:
                printf("Enter distance in centimeters (cm): ");
                scanf("%lf", &value);
                result = value / 100.0;
                printf("%.2lf cm is equal to %.2lf meters.\n", value, result);
                break;
            case 5:
                printf("Enter distance in kilometers (km): ");
                scanf("%lf", &value);
                result = value * 100000.0;
                printf("%.2lf km is equal to %.2lf centimeters.\n", value, result);
                break;
            case 6:
                printf("EXIT!\n");
                break;
            default:
                printf("Invalid choice. Please enter a number between 1 and 6.\n");
                break;
        }
    }

    return 0;
}
