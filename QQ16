#include <stdio.h>

int main() {
    int choice;
    float temperature, convertedTemp; // MENU DRIVEN PROGRAM - to convert temperature
    printf("Temperature Conversion Menu:\n");
    printf("1. Convert Celsius to Fahrenheit\n");
    printf("2. Convert Fahrenheit to Celsius\n");
    printf("Enter your choice (1 or 2): ");
    scanf("%d", &choice);
    switch (choice) {
        case 1:
            printf("Enter temperature in Celsius: ");
            scanf("%f", &temperature);
            convertedTemp = (temperature * 9.0 / 5.0) + 32.0;
            printf("%.2f Celsius is equal to %.2f Fahrenheit\n", temperature, convertedTemp);
            break; 

        case 2:
            printf("Enter temperature in Fahrenheit: ");
            scanf("%f", &temperature);
            convertedTemp = (temperature - 32.0) * 5.0 / 9.0;
            printf("%.2f Fahrenheit is equal to %.2f Celsius\n", temperature, convertedTemp);
            break;

        default:
            printf("Invalid choice. Please enter 1 or 2.\n");
            break; 
    }

    return 0;
}
